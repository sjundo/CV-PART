cmake_minimum_required(VERSION 3.5)
project(tomato_detection)

# ...

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()

ament_package()

