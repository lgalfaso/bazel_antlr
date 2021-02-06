
java_library(
    name = "utils",
    srcs = glob(["src/com/tools/utils/*.java"]),
    visibility = ["//visibility:public"],
)

java_binary(
    name = "antlr",
    srcs = glob(["src/com/tools/binaries/*.java"]),
    main_class = "com.tools.binaries.AntlrCompiler",
    visibility = ["//visibility:public"],
    deps = [
        ":utils",
        "@maven//:org_antlr_antlr4",
    ],
)
