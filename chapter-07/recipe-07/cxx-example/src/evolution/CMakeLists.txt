add_library(evolution "")
message(STATUS CMAKE_CURRENT_LIST_DIR is ${CMAKE_CURRENT_LIST_DIR})
target_sources(evolution
  PRIVATE
    evolution.cpp
  PUBLIC
    ${CMAKE_CURRENT_LIST_DIR}/evolution.hpp
  )

target_include_directories(evolution
  PUBLIC
    ${CMAKE_CURRENT_LIST_DIR}
  )
