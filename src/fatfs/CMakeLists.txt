# DO NOT EDIT! This file was automatically generated by `dbt buildgen`
# External but in-source libraries
add_library(fatfs STATIC
    ff.c
    ffsystem.c
    ffunicode.c
)
target_include_directories(fatfs PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
