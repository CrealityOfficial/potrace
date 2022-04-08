set(SRCS 
     auxiliary.h
     bbox.c
     bbox.h
     bitmap.h
     curve.c
     curve.h
     decompose.c
     decompose.h
     lists.h
     main.h
     potracelib.c
     potracelib.h
     progress.h
     progress_bar.c
     progress_bar.h
     trace.c
     trace.h
     trans.c
     trans.h
 )

__add_real_target(potrace lib SOURCE ${SRCS} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})