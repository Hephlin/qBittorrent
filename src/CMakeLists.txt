include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_subdirectory(app)
add_subdirectory(base)
add_subdirectory(boost)
add_subdirectory(ssh)
if (GUI)
    add_subdirectory(gui)
endif()

if (WEBUI)
    add_subdirectory(webui)
endif()
