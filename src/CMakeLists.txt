set(LIB_SOURCES student.cpp)
add_library(studentlib STATIC ${LIB_SOURCES})
target_include_directories(studentlib PUBLIC ${CMAKE_SOURCE_DIR}/include)