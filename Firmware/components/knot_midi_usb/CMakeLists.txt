idf_component_register(
    SRCS
        "knot_midi_usb.c"
    INCLUDE_DIRS
        "."
    REQUIRES
        "knot_midi_translator"
        "knot_midi_uart"
        "knot_midi_queue"
        "driver"
        "usb"
        "grid_common"
        "grid_esp32_led"
)
