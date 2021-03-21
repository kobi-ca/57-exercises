add_executable(exercise-1 main.cpp)

add_executable(exercise-1-test tests/exercise-1-test.cpp)
target_link_libraries(exercise-1-test PRIVATE ${CONAN_LIBS_GTEST})

add_test(NAME exercise-1-test  COMMAND exercise-1-test)
