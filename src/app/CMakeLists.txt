add_executable(${PROJECT_NAME} main.c)
target_link_libraries(${PROJECT_NAME} PUBLIC FREERTOS)
set_target_properties(${PROJECT_NAME}
   PROPERTIES
   CMAKE_RUNTIME_OUTPUT_DIRECTORY, ${CMAKE_SOURCE_DIR}
)