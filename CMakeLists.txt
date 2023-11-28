cmake_minimum_required (VERSION 3.28)

project ("kk_cpp" VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# FOR FUTURE REFERENCE - ignore for now.
# list(APPEND CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake/)
# include(doxygen_docs)


add_subdirectory(app)
add_subdirectory(src)
add_subdirectory(tests)
