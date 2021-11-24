cmake_minimum_required (VERSION 3.0)
project (mei-amt-check)

add_executable (mei-amt-check
  mei-amt-check.c
  )

install (TARGETS mei-amt-check DESTINATION bin)
