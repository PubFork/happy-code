add_executable(patfork pthread_atfork_test.cpp)
target_link_libraries(patfork pthread)

add_executable(pcond pthread_cond_test.cpp)
target_link_libraries(pcond pthread)

add_subdirectory(pthread_create)