add_executable(CustomConverter Main.cpp)
target_link_libraries(CustomConverter plog)
set_target_properties(CustomConverter PROPERTIES FOLDER Samples)