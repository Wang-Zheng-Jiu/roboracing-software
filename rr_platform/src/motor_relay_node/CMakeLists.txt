add_executable(motor_relay_node motor_relay_node.cpp)
target_link_libraries(motor_relay_node ${catkin_LIBRARIES} rr_serial)
add_dependencies(motor_relay_node ${catkin_EXPORTED_TARGETS})
