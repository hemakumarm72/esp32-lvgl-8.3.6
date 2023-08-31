

SET(SOURCES screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    )




idf_component_register(SRCS ${SOURCES}
                       REQUIRES lvgl
                       )


