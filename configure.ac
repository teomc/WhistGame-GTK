AC_PREREQ(2.59)

AC_INIT([whistGame], [0.2.0])

AC_CONFIG_AUX_DIR([config])
AC_CONFIG_HEADER([src/config.h])
AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE([subdir-objects])

AC_PROG_LIBTOOL

AC_CHECK_CUTTER
AM_CONDITIONAL(CUTTER, test x"$cutter_use_cutter" = x"yes")

AC_CONFIG_FILES([Makefile
                 src/Makefile
		 test/Makefile])

AC_OUTPUT