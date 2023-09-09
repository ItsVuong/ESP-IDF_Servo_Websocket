idf_component_register(SRCS "server.c" "connect_wifi.c" 
                    INCLUDE_DIRS ".")

spiffs_create_partition_image(storage ../data FLASH_IN_PROJECT)
