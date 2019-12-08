include_directories(
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)

add_library(binderthreadstate SHARED
        "IPCThreadStateBase.cpp"
)
#target_link_libraries(binder utils)

#add_subdirectory(tests)
