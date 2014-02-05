cc_library(
    name = 'libevhtp',
    srcs = [
        'evhtp.c',
    ],
    deps = [
        '#pthread',
        '//thirdparty/libevent:libevent',
        '//thirdparty/openssl:openssl',
        '//essence/libevhtp/evthr:evthr',
        '//essence/libevhtp/htparse:htparse',
    ],
    defs = [
        '_POSIX_C_SOURCE=200112',
    ],
    warning = 'no',
)

cc_binary(
    name = 'test_basic',
    warning = 'no',
    srcs = 'examples/test_basic.c',
    deps = [
        ':libevhtp',
    ],
)

cc_binary(
    name = 'test_client',
    warning = 'no',
    srcs = 'examples/test_client.c',
    deps = [
        ':libevhtp',
    ],
)

cc_binary(
    name = 'test_proxy',
    warning = 'no',
    srcs = 'examples/test_proxy.c',
    deps = [
        ':libevhtp',
    ],
)

cc_binary(
    name = 'test_vhost',
    warning = 'no',
    srcs = 'examples/test_vhost.c',
    deps = [
        ':libevhtp',
    ],
)

cc_binary(
    name = 'test',
    warning = 'no',
    srcs = 'examples/test.c',
    deps = [
        ':libevhtp',
    ],
)
