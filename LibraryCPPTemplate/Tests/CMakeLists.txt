add_executable(TestArrayCPPTemplate array.cpp)
target_include_directories(TestArrayCPPTemplate PUBLIC ..)
add_test(TestArrayCPPTemplate TestArrayCPPTemplate)

add_executable(TestListCPPTemplate list.cpp)
target_include_directories(TestListCPPTemplate PUBLIC ..)
add_test(TestListCPPTemplate TestListCPPTemplate)

add_executable(TestQueueCPPTemplate queue.cpp)
target_include_directories(TestQueueCPPTemplate PUBLIC ..)
add_test(TestQueueCPPTemplate TestQueueCPPTemplate)

add_executable(TestStackCPPTemplate stack.cpp)
target_include_directories(TestStackCPPTemplate PUBLIC ..)
add_test(TestStackCPPTemplate TestStackCPPTemplate)

add_executable(TestVectorCPPTemplate vector.cpp)
target_include_directories(TestVectorCPPTemplate PUBLIC ..)
add_test(TestVectorCPPTemplate TestVectorCPPTemplate)
set_tests_properties(TestVectorCPPTemplate PROPERTIES TIMEOUT 10)

add_executable(TestDirectedGraphCPPTemplate directed_graph.cpp)
target_include_directories(TestDirectedGraphCPPTemplate PUBLIC ..)
add_test(TestDirectedGraphCPPTemplate TestDirectedGraphCPPTemplate)

add_executable(TestAssociativeArrayCorrectnessCPPTemplate associative_array.cpp)
target_include_directories(TestAssociativeArrayCorrectnessCPPTemplate PUBLIC ..)
add_test(TestAssociativeArrayCorrectnessCPPTemplate TestAssociativeArrayCorrectnessCPPTemplate)
set_tests_properties(TestAssociativeArrayCorrectnessCPPTemplate PROPERTIES TIMEOUT 10)

add_executable(TestAssociativeArrayPerformanceCPPTemplate associative_array_performance.cpp)
target_include_directories(TestAssociativeArrayPerformanceCPPTemplate PUBLIC ..)
add_test(TestAssociativeArrayPerformanceCPPTemplate TestAssociativeArrayPerformanceCPPTemplate)
set_tests_properties(TestAssociativeArrayPerformanceCPPTemplate PROPERTIES TIMEOUT 10)

add_executable(TestString string_performance.cpp)
target_include_directories(TestString PUBLIC ..)
add_test(TestString TestString)
