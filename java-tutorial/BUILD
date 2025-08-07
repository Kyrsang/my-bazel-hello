load("@rules_java//java:defs.bzl", "java_binary")

java = use_extension("@rules_java//java:extensions.bzl", "java")
java.toolchain(
    version = "11",
)

package(default_visibility = ["//visibility:public"])

java_binary(
    name = "ProjectRunner",
    srcs = glob(["src/main/java/com/example/*.java"]),
)