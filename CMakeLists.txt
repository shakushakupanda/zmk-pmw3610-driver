zephyr_library()

zephyr_library_sources_ifdef(CONFIG_INPUT_PAW32XX pwm3610.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
