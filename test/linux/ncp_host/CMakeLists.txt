
set(SOURCES ncp_host.c)
add_executable(ncp_host ${SOURCES})
target_link_libraries(ncp_host soem)
install(TARGETS ncp_host DESTINATION bin)
