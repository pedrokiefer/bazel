# Description:
#   Genquery support

package(
    default_visibility = ["//src:__subpackages__"],
)

java_library(
    name = "genquery",
    srcs = glob(["*.java"]),
    deps = [
        "//src/main/java/com/google/devtools/build/lib:build-base",
        "//src/main/java/com/google/devtools/build/lib:collect",
        "//src/main/java/com/google/devtools/build/lib:common",
        "//src/main/java/com/google/devtools/build/lib:events",
        "//src/main/java/com/google/devtools/build/lib:packages-internal",
        "//src/main/java/com/google/devtools/build/lib:util",
        "//src/main/java/com/google/devtools/build/lib:vfs",
        "//src/main/java/com/google/devtools/build/lib/actions",
        "//src/main/java/com/google/devtools/build/lib/query2",
        "//src/main/java/com/google/devtools/build/lib/query2:query-engine",
        "//src/main/java/com/google/devtools/build/lib/query2:query-output",
        "//src/main/java/com/google/devtools/build/skyframe",
        "//src/main/java/com/google/devtools/common/options",
        "//third_party:jsr305",
        "//third_party:protobuf",
    ],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)
