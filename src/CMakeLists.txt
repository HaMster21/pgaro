project(pigaroctl)
find_package(Boost REQUIRED system)
add_executable(pigaroctl main.cpp)
target_link_libraries(pigaroctl ${Boost_LIBRARY_DIRS})
