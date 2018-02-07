<<<<<<< 6b9796c310edeb4edea4a311eb14b6409bd77b9c
# Copyright (c) 2018 Linaro Limited
#
# SPDX-License-Identifier: Apache-2.0
#

add_subdirectory_ifdef(CONFIG_OPENAMP open-amp)

add_subdirectory_ifdef(IPC_RPMSG_LITE rpmsg_lite)
