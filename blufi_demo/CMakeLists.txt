#===============================================================================
# @brief    cmake file
# Copyright (c) CompanyNameMagicTag 2023-2023. All rights reserved.
#===============================================================================
set(SOURCES_LIST
    ${CMAKE_CURRENT_SOURCE_DIR}/blufi.c
    ${CMAKE_CURRENT_SOURCE_DIR}/blufi_adv.c
    ${CMAKE_CURRENT_SOURCE_DIR}/blufi_protocol.c
    ${CMAKE_CURRENT_SOURCE_DIR}/blufi_event.c
)   
set(SOURCES "${SOURCES}" ${SOURCES_LIST} PARENT_SCOPE)
