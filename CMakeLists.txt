project (jotkacy)

#version number
set (jotkacy_VERSION_MAJOR 1)
set (jotkacy_VERSION_MINOR 0)

add_executable (jotkacy main.c)

install (TARGETS jotkacy DESTINATION bin)
