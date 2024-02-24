build_lib_example(
    NAME tcp-friendly-same-initcwnd
    SOURCE_FILES tcp-friendly-same-initcwnd.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME tcp-friendly-different-initcwnd
    SOURCE_FILES tcp-friendly-different-initcwnd.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME aggressive-transport-sender
    SOURCE_FILES aggressive-transport-sender.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME heavy-congestion
    SOURCE_FILES heavy-congestion.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME medium-congestion
    SOURCE_FILES medium-congestion.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME mild-congestion
    SOURCE_FILES mild-congestion.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME rtt-fairness
    SOURCE_FILES rtt-fairness.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)

build_lib_example(
    NAME unresponsive-with-friendly-transport
    SOURCE_FILES unresponsive-with-friendly-transport.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME varying-congestion
    SOURCE_FILES vary-congestion-level.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME varying-bandwidth-uno
    SOURCE_FILES vary-available-capacity-uno.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME varying-bandwidth-duo
    SOURCE_FILES vary-available-capacity-duo.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME lbe-transport-sender
    SOURCE_FILES LBE-transport-sender.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME single-unresponsive-transport
    SOURCE_FILES single-unresponsive-transport.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)
build_lib_example(
    NAME aqm-eval-suite-runner
    SOURCE_FILES aqm-eval-suite-runner.cc
    LIBRARIES_TO_LINK 
    ${libnew-aqm-eval-suite}
    ${libcore}
    ${libinternet}
    ${libpoint-to-point}
    ${libapplications}
    ${libpoint-to-point-layout}
)

