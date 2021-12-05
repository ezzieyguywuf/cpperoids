add_executable(cpperoids main.cpp)

# if(MYCAD_VULKAN_VIEWER)
#     find_package(Vulkan REQUIRED)
#     add_executable(mycad-vk vulkan_main.cpp vulkan_helpers.cpp render_helpers.cpp)
#     target_link_libraries(mycad-vk glfw ${Vulkan_LIBRARIES} ${CMAKE_DL_LIBS} glm::glm mycad-geometry mycad-entity mycad-topology)
# endif()
