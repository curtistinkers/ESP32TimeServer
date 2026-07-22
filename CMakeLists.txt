# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(ESP32TimeServer
        VERSION 2.2.1
        SPDX_LICENSE MIT
        DESCRIPTION "ESP32 NTP Stratum 1 Time Server for your home network"
        HOMEPAGE_URL "https://github.com/roblatour/ESP32TimeServer"
        )

