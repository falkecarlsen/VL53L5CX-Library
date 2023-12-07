cmake_minimum_required(VERSION 3.5)

idf_component_register(
    SRCS 
        "vl53l5cx_api.c" 
        "vl53l5cx_plugin_detection_thresholds.c" 
        "vl53l5cx_plugin_motion_indicator.c" 
        "vl53l5cx_plugin_xtalk.c" 
        "platform.c" 
        "examples/Example_1_ranging_basic.c"
        "examples/Example_2_get_set_params.c"
        "examples/Example_3_ranging_modes.c"
        "examples/Example_4_power_modes.c"
        "examples/Example_6_I2C_and_RAM_optimization.c"
        "examples/Example_7_calibrate_xtalk.c"
        "examples/Example_8_vizualize_xtalk_data.c"
        "examples/Example_9_detection_thresholds.c"
        "examples/Example_10_motion_indicator.c"
        "examples/Example_11_motion_indicator_with_detection_thresholds.c"
    INCLUDE_DIRS 
        "include" 
    REQUIRES 
        "driver"
        )