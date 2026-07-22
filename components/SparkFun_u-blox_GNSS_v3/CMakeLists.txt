# Register the component locally using paths pointing to your clean 3rdparty submodule
idf_component_register(
    SRCS 
        "../../3rdparty/SparkFun_u-blox_GNSS_v3/src/sfe_bus.cpp"
        "../../3rdparty/SparkFun_u-blox_GNSS_v3/src/u-blox_GNSS.cpp"
    INCLUDE_DIRS 
        "../../3rdparty/SparkFun_u-blox_GNSS_v3/src"
    REQUIRES 
        arduino-esp32
)
