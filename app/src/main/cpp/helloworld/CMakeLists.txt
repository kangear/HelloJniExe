add_executable (
    # name
    helloworld

    # source
    ${CMAKE_CURRENT_SOURCE_DIR}/helloworld.c
    )

# helloworld, in this example, has mylib as dependency
target_link_libraries(helloworld)
