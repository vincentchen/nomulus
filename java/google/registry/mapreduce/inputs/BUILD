package(
    default_visibility = ["//java/google/registry:registry_project"],
)

licenses(["notice"])  # Apache 2.0


java_library(
    name = "inputs",
    srcs = glob(["*.java"]),
    visibility = ["//visibility:public"],
    deps = [
        "//java/com/google/common/annotations",
        "//java/com/google/common/base",
        "//java/com/google/common/collect",
        "//third_party/java/appengine:appengine-api",
        "//third_party/java/appengine_mapreduce2:appengine_mapreduce",
        "//third_party/java/appengine_pipeline",
        "//third_party/java/dagger",
        "//third_party/java/joda_time",
        "//third_party/java/jsr330_inject",
        "//third_party/java/objectify:objectify-v4_1",
        "//third_party/java/servlet/servlet_api",
        "//java/google/registry/model",
        "//java/google/registry/util",
    ],
)
