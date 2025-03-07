zephyr_library()

zephyr_library_sources_ifdef(CCONFIG_INPUT_PAW32XX src/pmw3610.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
