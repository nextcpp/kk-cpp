add_library(kkMD)
target_sources(kkMD PRIVATE
               FILE_SET cxx_modules
               TYPE CXX_MODULES
               FILES 
                   kk.ixx
                   partitions/kk-world.ixx)

target_link_libraries(kkMD PRIVATE utilsMD)