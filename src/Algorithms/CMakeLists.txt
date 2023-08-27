set(HEADER_FILES ${PROJECT_SOURCE_DIR}/include/Sorting.h)

add_library(Algorithms STATIC Sorting.cpp ${HEADER_FILES})

target_include_directories(Algorithms INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
