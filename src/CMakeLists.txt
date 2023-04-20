add_library(CloxLib
    chunk.c
    debug.c
    memory.c
    value.c)

target_link_libraries(clox PRIVATE CloxLib)