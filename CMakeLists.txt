cmake_minimum_required(VERSION 3.10)

project(MyGuiApp)

find_package(SFML 2.5 COMPONENTS graphics window system REQUIRED)

add_executable(
    main.cpp
)

target_link_libraries(MyGuiApp sfml-graphics sfml-window sfml-system)