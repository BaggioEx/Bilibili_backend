filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//app/job/bbq/comment/cmd:all-srcs",
        "//app/job/bbq/comment/internal/dao:all-srcs",
        "//app/job/bbq/comment/internal/model:all-srcs",
        "//app/job/bbq/comment/internal/server/http:all-srcs",
        "//app/job/bbq/comment/internal/service:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
