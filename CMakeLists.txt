idf_component_register(SRCS "cmd_ping.c" "drv_ping.c"
                    INCLUDE_DIRS "." 
                    REQUIRES "lwip" "console" "drv_console"
                                      )
                 

