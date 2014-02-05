cc_library(
    name = 'evthr',
    warning = 'no',
    srcs = [
        'evthr.c',
    ],
    deps = [
        '//thirdparty/libevent:libevent'
    ]
)

cc_binary(
    name = 'test',
    warning = 'no',
    srcs = [
        'test.c',
    ],
    deps = [
        ':evthr',
    ]
)
