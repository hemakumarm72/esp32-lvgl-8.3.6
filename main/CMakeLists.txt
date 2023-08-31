# SET(SOURCES ui/screens/ui_Screen1.c
#     ui/ui.c
#     ui/components/ui_comp_hook.c
#     ui/ui_helpers.c
#     REQUIRES lvgl
#     )



idf_component_register(SRCS "vehicle_lvgl.c" 
                       INCLUDE_DIRS "."
                      )




target_compile_definitions(${COMPONENT_LIB} PUBLIC "-DLOG_LOCAL_LEVEL=ESP_LOG_VERBOSE")



