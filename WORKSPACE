git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    commit = "05bf1b2adfbfe4e77552f25e3331e14865bff586",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories", "new_go_repository")

#TODO: omit_go=True and put the go tarball on artifactory
go_repositories()
