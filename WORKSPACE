workspace(
    name = "com_zombiezen_mcm",
)

git_repository(
    name = "boringssl",
    remote = "https://boringssl.googlesource.com/boringssl",
    commit = "a868baebef9e7d95cee60baaf8aa420046c9300c",
)

git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.3.0",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories")

go_repositories()