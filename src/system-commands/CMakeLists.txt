
add_library(system-commands sys-commands.c)
target_include_directories(system-commands INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}
)
target_include_directories(system-commands PRIVATE
    ${PROJECT_LIB_FOLDER}
)
