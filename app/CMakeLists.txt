set(APP_SOURCES mainapp.cpp)
add_executable(mainstudent ${APP_SOURCES})
target_link_libraries(mainstudent studentlib)