add_library(raylibpp src/core/window.cpp)
target_include_directories(raylibpp PUBLIC src/include)

add_subdirectory(raylib)
target_link_libraries(raylibpp raylib)
