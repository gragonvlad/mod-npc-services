CU_SET_PATH("CMAKE_Npc_Services_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/Npc_Services.cpp")

AC_ADD_SCRIPT_LOADER("Npc_Services"      "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

message("-- NPC SERVICES Stone CONFIGURED --")
