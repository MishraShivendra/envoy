licenses(["notice"])  # Apache 2

load(
    "//bazel:envoy_build_system.bzl",
    "envoy_cc_library",
    "envoy_package",
)

envoy_package()

envoy_cc_library(
    name = "api_interface",
    hdrs = ["api.h"],
    deps = [
        "//include/envoy/event:dispatcher_interface",
        "//include/envoy/thread:thread_interface",
    ],
)

envoy_cc_library(
    name = "os_sys_calls_interface",
    hdrs = ["os_sys_calls.h"],
)
