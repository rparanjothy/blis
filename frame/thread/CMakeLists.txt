##Copyright (C) 2020, Advanced Micro Devices, Inc.## 

target_sources("${PROJECT_NAME}"
    PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_openmp.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_openmp.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_pthreads.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_pthreads.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_single.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_decor_single.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_openmp.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_openmp.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_pthreads.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_pthreads.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_single.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_l3_sup_decor_single.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_pthread.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_pthread.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_openmp.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_openmp.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_pthreads.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_pthreads.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_single.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrcomm_single.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thread.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thread.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrinfo.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrinfo.h
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrinfo_sup.c
    ${CMAKE_CURRENT_SOURCE_DIR}/bli_thrinfo_sup.h	
	)
