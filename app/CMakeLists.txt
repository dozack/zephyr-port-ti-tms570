cmake_minimum_required(VERSION 3.20)

find_package(Zephyr)
project(tms570_port_init)

target_sources(app PRIVATE src/main.c)