scala_library(
    sources = rglobs("*.scala"),
    compiler_option_sets = {"fatal_warnings"},
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "finatra/examples/example-twitter-server/src/main/resources",
        "finatra/inject/inject-logback/src/main/scala",
        "finatra/inject/inject-server/src/main/scala",
        "finatra/inject/inject-slf4j/src/main/scala",
        "finatra/utils/src/main/scala",
    ],
)
