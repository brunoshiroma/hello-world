#check build arch

AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = hello_world

if TARGET_ARCH_X64
hello_world_SOURCES = hello_linux_x64.s
else
endif

## MAKE IT WORK !!!!
#if TARGET_ARCH_ARM
#hello_world_SOURCES = hello_linux_arm.s
#else
#endif

CFLAGS= -static
hello_world_LDFLAGS=-nostdlib -e_start