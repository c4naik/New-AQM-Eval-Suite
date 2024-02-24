check_include_file_cxx(stdint.h HAVE_STDINT_H)
if(HAVE_STDINT_H)
    add_definitions(-DHAVE_STDINT_H)
endif()

set(examples_as_tests_sources)
if(${ENABLE_EXAMPLES})
    set(examples_as_tests_sources
        #test/new-aqm-eval-suite-examples-test-suite.cc
        )
endif()

build_lib(
    LIBNAME new-aqm-eval-suite
    SOURCE_FILES model/eval-topology.cc
                 model/eval-app.cc
                 model/eval-ts.cc
                 helper/aqm-eval-suite-helper.cc
    HEADER_FILES model/eval-topology.h
                 model/eval-app.h
                 model/eval-ts.h
                 helper/aqm-eval-suite-helper.h
    LIBRARIES_TO_LINK 
    ${libcore}
    ${libnetwork}
    ${libinternet}
    
)

