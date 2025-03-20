#
# Copyright (c) 2019 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-Nordic-5-Clause
#
zephyr_library()

zephyr_library_sources(src/paw3222.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
