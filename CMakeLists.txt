add_library(pugixml STATIC ${CMAKE_CURRENT_SOURCE_DIR}/src/pugixml.cpp)
target_include_directories(pugixml INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/src)
