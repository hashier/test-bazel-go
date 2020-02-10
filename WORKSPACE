load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    urls = [
        "https://storage.googleapis.com/bazel-mirror/github.com/bazelbuild/rules_go/releases/download/v0.20.2/rules_go-v0.20.2.tar.gz",
        "https://github.com/bazelbuild/rules_go/releases/download/v0.20.2/rules_go-v0.20.2.tar.gz",
    ],
    sha256 = "b9aa86ec08a292b97ec4591cf578e020b35f98e12173bbd4a921f84f583aebd9",
)

http_archive(
    name = "bazel_gazelle",
    urls = [
        "https://storage.googleapis.com/bazel-mirror/github.com/bazelbuild/bazel-gazelle/releases/download/0.19.0/bazel-gazelle-0.19.0.tar.gz",
        "https://github.com/bazelbuild/bazel-gazelle/releases/download/v0.19.0/bazel-gazelle-v0.19.0.tar.gz",
    ],
    sha256 = "41bff2a0b32b02f20c227d234aa25ef3783998e5453f7eade929704dcff7cd4b",
)

load("@io_bazel_rules_go//go:deps.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "com_github_chzyer_readline",
    importpath = "github.com/chzyer/readline",
    sum = "h1:fY5BOSpyZCqRo5OhCuC+XN+r/bBCmeuuJtjz+bCNIf8=",
    version = "v0.0.0-20180603132655-2972be24d48e",
)

go_repository(
    name = "net_starlark_go",
    importpath = "go.starlark.net",
    sum = "h1:WR7X1xgXJlXhQBdorVc9Db3RhwG+J/kp6bLuMyJjfVw=",
    version = "v0.0.0-20190919145610-979af19b165c",
)

go_repository(
    name = "org_golang_x_sys",
    importpath = "golang.org/x/sys",
    sum = "h1:Vco5b+cuG5NNfORVxZy6bYZQ7rsigisU1WQFkvQ0L5E=",
    version = "v0.0.0-20191002063906-3421d5a6bb1c",
)

go_repository(
    name = "com_github_golang_protobuf",
    importpath = "github.com/golang/protobuf",
    sum = "h1:P3YflyNX/ehuJFLhxviNdFxQPkGK5cDcApsge1SqnvM=",
    version = "v1.2.0",
)

go_repository(
    name = "com_github_google_go_github_v28",
    importpath = "github.com/google/go-github/v28",
    sum = "h1:kORf5ekX5qwXO2mGzXXOjMe/g6ap8ahVe0sBEulhSxo=",
    version = "v28.1.1",
)

go_repository(
    name = "com_github_google_go_querystring",
    importpath = "github.com/google/go-querystring",
    sum = "h1:Xkwi/a1rcvNg1PPYe5vI8GbeBY/jrVuDX5ASuANWTrk=",
    version = "v1.0.0",
)

go_repository(
    name = "org_golang_google_appengine",
    importpath = "google.golang.org/appengine",
    sum = "h1:igQkv0AAhEIvTEpD5LIpAfav2eeVO9HBTjvKHVJPRSs=",
    version = "v1.1.0",
)

go_repository(
    name = "org_golang_x_crypto",
    importpath = "golang.org/x/crypto",
    sum = "h1:VklqNMn3ovrHsnt90PveolxSbWFaJdECFbxSq0Mqo2M=",
    version = "v0.0.0-20190308221718-c2843e01d9a2",
)

go_repository(
    name = "org_golang_x_net",
    importpath = "golang.org/x/net",
    sum = "h1:oWX7TPOiFAMXLq8o0ikBYfCJVlRHBcsciT5bXOrH628=",
    version = "v0.0.0-20190311183353-d8887717615a",
)

go_repository(
    name = "org_golang_x_oauth2",
    importpath = "golang.org/x/oauth2",
    sum = "h1:vEDujvNQGv4jgYKudGeI/+DAX4Jffq6hpD55MmoEvKs=",
    version = "v0.0.0-20180821212333-d2e6202438be",
)

go_repository(
    name = "org_golang_x_sync",
    importpath = "golang.org/x/sync",
    sum = "h1:bjcUS9ztw9kFmmIxJInhon/0Is3p+EHBKNgquIzo1OI=",
    version = "v0.0.0-20190227155943-e225da77a7e6",
)

go_repository(
    name = "org_golang_x_text",
    importpath = "golang.org/x/text",
    sum = "h1:g61tztE5qeGQ89tm6NTjjM9VPIm088od1l6aSorWRWg=",
    version = "v0.3.0",
)

go_repository(
    name = "com_github_blang_semver",
    importpath = "github.com/blang/semver",
    sum = "h1:cQNTCjp13qL8KC3Nbxr/y2Bqb63oX6wdnnjpJbkM4JQ=",
    version = "v3.5.1+incompatible",
)

go_repository(
    name = "com_github_davecgh_go_spew",
    importpath = "github.com/davecgh/go-spew",
    sum = "h1:ZDRjVQ15GmhC3fiQ8ni8+OwkZQO4DARzQgrnXU1Liz8=",
    version = "v1.1.0",
)

go_repository(
    name = "com_github_pmezard_go_difflib",
    importpath = "github.com/pmezard/go-difflib",
    sum = "h1:4DBwDE0NGyQoBHbLQYPwSUPoCMWR5BEzIk/f1lZbAQM=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_stretchr_objx",
    importpath = "github.com/stretchr/objx",
    sum = "h1:4G4v2dO3VZwixGIRoQ5Lfboy6nUhCyYzaqnIAPPhYs4=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_stretchr_testify",
    importpath = "github.com/stretchr/testify",
    sum = "h1:2E4SXV/wtOkTonXsotYi4li6zVWxYlZuYNCXe9XRJyk=",
    version = "v1.4.0",
)

go_repository(
    name = "in_gopkg_check_v1",
    importpath = "gopkg.in/check.v1",
    sum = "h1:yhCVgyC4o1eVCa2tZl7eS0r+SDo693bJlVdllGtEeKM=",
    version = "v0.0.0-20161208181325-20d25e280405",
)

go_repository(
    name = "in_gopkg_yaml_v2",
    importpath = "gopkg.in/yaml.v2",
    sum = "h1:ZCJp+EgiOT7lHqUV2J862kp8Qj64Jo6az82+3Td9dZw=",
    version = "v2.2.2",
)

maven_jar(
    name = "io_dropwizard_dropwizard_core",
    artifact = "io.dropwizard:dropwizard-core:0.7.1",
    sha1 = "569cd6181d5fea4b033cf3a0eca632c8931a1a3a",
)

maven_jar(
    name = "io_dropwizard_dropwizard_testing",
    artifact = "io.dropwizard:dropwizard-testing:0.7.1",
    sha1 = "200d34e61674d73595055e809fca013aee0a4250",
)

maven_jar(
    name = "io_dropwizard_dropwizard_client",
    artifact = "io.dropwizard:dropwizard-client:0.7.1",
    sha1 = "7cef9884395e90a4dc627e643f84b48a2ff6fb30",
)

maven_jar(
    name = "io_dropwizard_dropwizard_jetty",
    artifact = "io.dropwizard:dropwizard-jetty:0.7.1",
    sha1 = "269303642030a9e093b4cc19e8036e174113a04a",
)

maven_jar(
    name = "io_dropwizard_dropwizard_logging",
    artifact = "io.dropwizard:dropwizard-logging:0.7.1",
    sha1 = "039d41453b0cb37c4c6239566ccb52787a68d270",
)

maven_jar(
    name = "io_dropwizard_dropwizard_validation",
    artifact = "io.dropwizard:dropwizard-validation:0.7.1",
    sha1 = "59a73cdcab2489b6dd342926bb4250e9c62e6938",
)

maven_jar(
    name = "io_dropwizard_dropwizard_metrics",
    artifact = "io.dropwizard:dropwizard-metrics:0.7.1",
    sha1 = "6ca1d7d1d1d1bcf7c803a127e0c6696d1c98fdb1",
)

maven_jar(
    name = "org_apache_thrift_libthrift",
    artifact = "org.apache.thrift:libthrift:0.9.2",
    sha1 = "9b067e2e2c5291e9f0d8b3561b1654286e6d81ee",
)

maven_jar(
    name = "oauth_signpost_signpost_commonshttp4",
    artifact = "oauth.signpost:signpost-commonshttp4:1.2",
    sha1 = "1054da42a9c8e2acfbdf875cecebec047557a83f",
)

maven_jar(
    name = "io_dropwizard_dropwizard_jackson",
    artifact = "io.dropwizard:dropwizard-jackson:0.7.1",
    sha1 = "6bc655d16acdb556001b1d677fab6c69f7ba296a",
)

maven_jar(
    name = "io_dropwizard_dropwizard_util",
    artifact = "io.dropwizard:dropwizard-util:0.7.1",
    sha1 = "49c3b2764b4f6ad1a97ae7148ac8a640488b0b29",
)

maven_jar(
    name = "io_dropwizard_dropwizard_configuration",
    artifact = "io.dropwizard:dropwizard-configuration:0.7.1",
    sha1 = "161539b50579dffbcd00eff796adc2020c02a6f9",
)

maven_jar(
    name = "io_dropwizard_dropwizard_metrics_graphite",
    artifact = "io.dropwizard:dropwizard-metrics-graphite:0.7.1",
    sha1 = "fa2d12fb3f9367d96ba6282a9081a4444bc1d426",
)

maven_jar(
    name = "org_bouncycastle_bcprov_jdk15",
    artifact = "org.bouncycastle:bcprov-jdk15:1.46",
    sha1 = "d726ceb2dcc711ef066cc639c12d856128ea1ef1",
)

maven_jar(
    name = "asm_asm",
    artifact = "asm:asm:3.1",
    sha1 = "c157def142714c544bdea2e6144645702adf7097",
)

maven_jar(
    name = "io_dropwizard_dropwizard_lifecycle",
    artifact = "io.dropwizard:dropwizard-lifecycle:0.7.1",
    sha1 = "12c282d9682628d7c33654e0d62f1dbf2a883d20",
)

maven_jar(
    name = "io_dropwizard_dropwizard_servlets",
    artifact = "io.dropwizard:dropwizard-servlets:0.7.1",
    sha1 = "b9d2016bbeb2df39cc90632338923273d708b55e",
)

maven_jar(
    name = "com_google_zxing_qrcode_core",
    artifact = "com.google.zxing:core:3.3.3",
    sha1 = "b640badcc97f18867c4dfd249ef8d20ec0204c07",
)

maven_jar(
    name = "com_google_zxing_qrcode_javase",
    artifact = "com.google.zxing:javase:3.3.3",
    sha1 = "44d02048349c96eacb394af7978b3e6f1777bb02",
)

maven_jar(
    name = "org_apache_hadoop_hadoop_core",
    artifact = "org.apache.hadoop:hadoop-core:1.2.1",
    sha1 = "3e5874122a26a735162a380627210779b41bfd59",
)
