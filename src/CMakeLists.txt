add_executable(modulestest main.cpp "test.ixx")

target_compile_features(modulestest PRIVATE cxx_std_23)
set_target_properties(modulestest PROPERTIES CXX_EXTENSIONS OFF)