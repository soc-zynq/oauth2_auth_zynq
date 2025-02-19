# Create a library called "oauth2_auth_zynq"
add_library(oauth2_auth_zynq_lib oauth2_auth_zynq.cpp)

# Specify include directories for the library
target_include_directories(oauth2_auth_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
