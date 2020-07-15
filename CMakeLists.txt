cmake_minimum_required(version 3.7)
project("OBJ_Loader")
add_library(obj_loader INTERFACE)
target_include_directories(obj_loader INTERFACE "${CMAKE_CURRENT_LIST_DIR}/include")


