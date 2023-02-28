if(CC_INSTALL_STB)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ stb)
endif()

add_library(stb INTERFACE)
set_property(TARGET stb PROPERTY INTERFACE_INCLUDE_DIRECTORIES ${CMAKE_CURRENT_SOURCE_DIR})