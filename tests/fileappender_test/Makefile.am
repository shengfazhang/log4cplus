noinst_PROGRAMS += fileappender_test

fileappender_test_sources = %D%/main.cxx
fileappender_test_SOURCES = $(fileappender_test_sources)

fileappender_test_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += fileappender_testU
fileappender_testU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
fileappender_testU_SOURCES = $(fileappender_test_sources)
fileappender_testU_LDADD = $(liblog4cplusU_la_file)
endif
