# @generated: This file was generated by bzl. Do not modify!
# Argument overrides and custom targets should be specified in BUILD.in.

load("//build_tools/go:go.bzl", "dbx_go_library")

dbx_go_library(
    name = "jsonfuzz",
    srcs = [
        "fuzz.go",
    ],
    visibility = [
        "//go/src/google.golang.org/protobuf:__subpackages__",
    ],
    deps = [
        "//go/src/google.golang.org/protobuf/encoding/protojson",
        "//go/src/google.golang.org/protobuf/internal/testprotos/fuzz",
        "//go/src/google.golang.org/protobuf/proto",
    ],
)
