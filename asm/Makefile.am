#check build arch

AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = hello_world

if TARGET_ARCH_X64
hello_world_SOURCES = hello_linux_x64.s 
else
hello_world_SOURCES = hello_linux_arm.s
endif

CFLAGS= -static
hello_world_LDFLAGS=-nostdlib -e_start