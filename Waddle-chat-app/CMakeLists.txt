# CMakeList.txt : CMake project for Waddle-chat-app, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Waddle-chat-app "Waddle-chat-app.cpp" "Waddle-chat-app.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Waddle-chat-app PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
