set(Physx_DIR "${CMAKE_CURRENT_SOURCE_DIR}/Vendors/PhysX")
find_package(Physx)

if(Physx_FOUND)
else(Physx_FOUND)
    message(FATAL_ERROR "Physx library not found")
endif(Physx_FOUND)

add_subdirectory(Vendors)
add_subdirectory(Runtime)
add_subdirectory(App)