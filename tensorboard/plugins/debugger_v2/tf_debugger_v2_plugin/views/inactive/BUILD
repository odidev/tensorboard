load("@npm_angular_bazel//:index.bzl", "ng_module")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])  # Apache 2.0

ng_module(
    name = "inactive",
    srcs = [
        "inactive_component.ts",
        "inactive_container.ts",
        "inactive_module.ts",
    ],
    assets = [
        "inactive_component.css",
        "inactive_component.ng.html",
    ],
    deps = [
        "@npm//@angular/core",
        "@npm//@ngrx/store",
        "@npm//rxjs",
    ],
)
