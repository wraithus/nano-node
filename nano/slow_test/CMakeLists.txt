add_executable(slow_test entry.cpp node.cpp)

target_link_libraries(
  slow_test
  secure
  node
  test_common
  gtest
  libminiupnpc-static
  Boost::boost)
