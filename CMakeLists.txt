#
# C++ untar library
#

set (SOURCES
		src/untar.cpp
	)

add_library(untar ${SOURCES})
target_compile_features(untar PUBLIC cxx_std_17)
target_include_directories(untar PUBLIC include)
