##Copyright (C) 2020, Advanced Micro Devices, Inc.## 

target_sources("${PROJECT_NAME}" 
     PRIVATE
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rd_zen_asm_s6x16.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rd_zen_asm_s6x16m.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rd_zen_asm_s6x16n.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_c3x8.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_c3x8m.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_c3x8n.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_s6x16.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_s6x16m.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_s6x16n.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_z3x4.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_z3x4m.c
${CMAKE_CURRENT_SOURCE_DIR}/bli_gemmsup_rv_zen_asm_z3x4n.c
    )
