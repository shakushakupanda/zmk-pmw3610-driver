zephyr_library()

zephyr_library_sources_ifdef(CONFIG_INPUT_PAW32XX input_paw32xx.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
