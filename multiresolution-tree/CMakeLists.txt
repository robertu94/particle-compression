project(multiresolution-tree)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(multiresolution-tree
    multiresolution-tree.cpp
    decode.cpp
    encode.cpp)
target_include_directories(multiresolution-tree
    PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}
    )

