# Copyright 2020-2021 Lucas Mirelmann

load("//third_party:antlr.bzl", "antlr_sources")

antlr_sources(
    name = "example_antlr_src",
    srcs = ["example.g4"],
    package = "com.tmh.example",
)

java_library(
    name = "example_antlr",
    srcs = [":example_antlr_src"],
    deps = ["@maven//:org_antlr_antlr4_runtime"],
    visibility = ["//visibility:public"],
)

