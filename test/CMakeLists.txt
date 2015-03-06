include(catch)
include(fakeit)
project(tests)

include_directories(${CATCH_INCLUDE_DIR} ${FAKEIT_INCLUDE_DIR})
enable_testing(true)

add_executable(tests test_main.cpp)
