#
# Copyright 2018 Ettus Research, a National Instruments Company
#
# SPDX-License-Identifier: GPL-3.0-or-later
#

########################################################################
# Build uhd_test static lib
########################################################################
include_directories("${CMAKE_SOURCE_DIR}/lib/include")
add_library(uhd_test
    ${CMAKE_CURRENT_SOURCE_DIR}/mock_zero_copy.cpp
)
