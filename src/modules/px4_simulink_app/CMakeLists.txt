## This is a place-holder cmakelist.txt file
## It will get replaced by the Pixhawk PSP

px4_add_module(
MODULE modules__px4_simulink_app
MAIN px4_simulink_app
STACK_MAIN 2000
SRCS
   empty_file.c   
DEPENDS
    platforms__common
)

