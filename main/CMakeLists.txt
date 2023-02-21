# list(APPEND srcs "app/src/test.c")
list(APPEND incdirs "app/inc")

list(APPEND srcs "main.c")
list(APPEND incdirs "inc")

idf_component_register(SRCS "${srcs}" INCLUDE_DIRS "${incdirs}" REQUIRES fwk)