#
# Copyright (c) 2026 Thomas Hebb
#
# SPDX-License-Identifier: Apache-2.0
#

if(CONFIG_NXP_IMXRT_BOOT_HEADER)
  zephyr_compile_definitions(BOARD_FLASH_SIZE=CONFIG_FLASH_SIZE*1024)
endif()
