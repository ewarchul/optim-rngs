add_executable(main main.cpp)
target_link_libraries(main fmt::fmt Eigen3::Eigen cmaes)
target_compile_features(main PRIVATE cxx_std_20)
