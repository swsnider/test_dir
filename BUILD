load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library", "go_prefix")

go_prefix("test_dir")

go_library(
    name = "go_default_library",
    srcs = ["t.go"],
    visibility = ["//visibility:private"],
    deps = ["//vendor/golang.org/x/sys/unix:go_default_library"],
)

go_binary(
    name = "test_dir",
    library = ":go_default_library",
    visibility = ["//visibility:public"],
)
