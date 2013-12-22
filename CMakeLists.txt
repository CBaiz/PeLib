set(LIBRARY_NAME_STR PeLib)

aux_source_directory(source SRCS)
aux_source_directory(source/buffer SRCS_BUFFER)

add_library(${LIBRARY_NAME_STR} STATIC ${SRCS} ${SRCS_BUFFER})
