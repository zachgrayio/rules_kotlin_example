load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_test")

kt_jvm_test(
    name = "test",
    srcs = [
        "MyTest.kt",
    ],
    test_class = "example.MyTest",
    deps = [
        "@maven//:junit_junit_4_13_1",
    ],
)