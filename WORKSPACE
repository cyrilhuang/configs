workspace(name = "configs")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "third_party",
    branch = "main",
    remote = "ssh://git@github.com/cyrilhuang/third_party.git",
)

git_repository(
    name = "p8n",
    branch = "main",
    remote = "ssh://git@github.com/cyrilhuang/p8n.git",
)
