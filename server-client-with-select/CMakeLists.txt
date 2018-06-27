cmake_minimum_required (VERSION 2.8)

project (sc_with_select C)

set(COMMON_HEADER "message.h")
add_executable (server ${COMMON_HEADER} server.c)
add_executable (client ${COMMON_HEADER} client.c)


