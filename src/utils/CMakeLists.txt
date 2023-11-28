add_library(utilsMD)
target_sources(utilsMD PRIVATE
               FILE_SET cxx_modules
               TYPE CXX_MODULES
               FILES utils.ixx)
# target_include_directories(utilsMD PUBLIC
#  "${CMAKE_SOURCE_DIR}/extern/include/"
# )

