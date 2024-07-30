cmake_minimum_required(VERSION 3.30.1)
project(cmakepractice)

set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_FLAGS_RELEASE "-O2")

include_directories(include)

#set(LIB_SOURCES src/student.cpp)
#set(APP_SOURCES app/mainapp.cpp)

#add_library(studentlib STATIC ${LIB_SOURCES})
#add_executable(mainstudent ${APP_SOURCES})  

#target_link_libraries(mainstudent studentlib)

add_subdirectory(src)
add_subdirectory(app)
