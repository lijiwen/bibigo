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
        "//app/interface/main/videoup/cmd:all-srcs",
        "//app/interface/main/videoup/conf:all-srcs",
        "//app/interface/main/videoup/dao/account:all-srcs",
        "//app/interface/main/videoup/dao/archive:all-srcs",
        "//app/interface/main/videoup/dao/bfs:all-srcs",
        "//app/interface/main/videoup/dao/creative:all-srcs",
        "//app/interface/main/videoup/dao/dynamic:all-srcs",
        "//app/interface/main/videoup/dao/elec:all-srcs",
        "//app/interface/main/videoup/dao/filter:all-srcs",
        "//app/interface/main/videoup/dao/geetest:all-srcs",
        "//app/interface/main/videoup/dao/mission:all-srcs",
        "//app/interface/main/videoup/dao/order:all-srcs",
        "//app/interface/main/videoup/dao/pay:all-srcs",
        "//app/interface/main/videoup/dao/subtitle:all-srcs",
        "//app/interface/main/videoup/dao/tag:all-srcs",
        "//app/interface/main/videoup/http:all-srcs",
        "//app/interface/main/videoup/model/archive:all-srcs",
        "//app/interface/main/videoup/model/geetest:all-srcs",
        "//app/interface/main/videoup/model/mission:all-srcs",
        "//app/interface/main/videoup/model/porder:all-srcs",
        "//app/interface/main/videoup/service:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
