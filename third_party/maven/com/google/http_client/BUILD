java_library(
    name = "google_http_client",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/http_client/google_http_client",
    ],
    runtime_deps = [
        "//third_party/maven/com/google/code/findbugs:jsr305",
        "//third_party/maven/com/google/guava",
        "//third_party/maven/com/google/j2objc:j2objc_annotations",
        "//third_party/maven/org/apache/httpcomponents:httpclient",
    ],
)

java_library(
    name = "google_http_client_appengine",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/http_client/google_http_client_appengine",
    ],
    runtime_deps = [
        ":google_http_client",
    ],
)

java_library(
    name = "google_http_client_gson",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/http_client/google_http_client_gson",
    ],
    runtime_deps = [
        ":google_http_client",
        "//third_party/maven/com/google/code/gson",
    ],
)

java_library(
    name = "google_http_client_jackson2",
    licenses = [
        "permissive",
    ],
    visibility = [
        "//third_party/maven:__subpackages__",
    ],
    exports = [
        "//external:jar/mvncom/google/http_client/google_http_client_jackson2",
    ],
    runtime_deps = [
        ":google_http_client",
        "//third_party/maven/com/fasterxml/jackson/core:jackson_core",
    ],
)
