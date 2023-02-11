# CMakeList.txt : CMake project for winsuck, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (winsuck_server "winsuck_server.cpp" "winsuck_server.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET winsuck_server PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
