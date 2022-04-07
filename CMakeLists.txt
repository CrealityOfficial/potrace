set(SRCS 
     auxiliary.h
     bbox.c
 )

__add_real_target(potrace lib SOURCE ${SRCS} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})