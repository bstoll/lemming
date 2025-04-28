load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "p4rt",
    srcs = ["p4rt.go"],
    importpath = "github.com/openconfig/lemming/p4rt",
    visibility = ["//visibility:public"],
    deps = [
        "@org_golang_google_grpc//:grpc",
        "@p4runtime//:p4runtime_go_proto",
    ],
)
