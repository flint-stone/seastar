cmake_minimum_required (VERSION 3.5)

project (SeastarExample)

#find_package (Seastar REQUIRED)

#add_executable (minimum
#  minimum.cc)

#target_link_libraries (minimum
#  PRIVATE Seastar::seastar)


find_package (Seastar REQUIRED)

add_executable (minimum
  minimum.cc)

target_link_libraries (minimum
  Seastar::seastar)
