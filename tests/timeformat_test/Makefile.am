noinst_PROGRAMS += timeformat_test

timeformat_test_sources = %D%/main.cxx
timeformat_test_SOURCES = $(timeformat_test_sources)

timeformat_test_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += timeformat_testU
timeformat_testU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
timeformat_testU_SOURCES = $(timeformat_test_sources)
timeformat_testU_LDADD = $(liblog4cplusU_la_file)
endif
