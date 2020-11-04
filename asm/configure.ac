AC_INIT([hello-world], [0.1], [brunoshiroma])
AM_INIT_AUTOMAKE([-Wall -Werror])
#AC_PROG_CC
AM_PROG_AS
AC_CONFIG_FILES([Makefile])
AC_OUTPUT

AS_IF([test `uname -m` = "x86_64"], [AC_DEFINE([TARGET_ARCH_X64], [1])])
AS_IF([test `uname -m` = "armv7l"], [AC_DEFINE([TARGET_ARCH_ARM], [1])])

AM_CONDITIONAL([TARGET_ARCH_X64], [test "x$TARGET_ARCH_X64" == "1"])
AM_CONDITIONAL([TARGET_ARCH_ARM], [test "x$TARGET_ARCH_ARM" == "1"])