java_binary(
    name = "everything",
    srcs = glob(["src/main/java/**/*.java"]),
    resources = glob(["src/main/resources/**"]),
		deps = [
      "@maven//:io_dropwizard_dropwizard_core",
      "@maven//:io_dropwizard_dropwizard_dependencies",
      "@maven//:io_dropwizard_metrics_metrics_annotation",
      "@maven//:javax_validation_validation_api",
      "@maven//:javax_ws_rs_javax_ws_rs_api",
      "@maven//:com_fasterxml_jackson_core_jackson_annotations",
      "@maven//:com_google_guava_guava",
      "@maven//:org_hibernate_validator_hibernate_validator",
      "@maven//:jakarta_validation_jakarta_validation_api",
    ],
    main_class = "edu.aij.MavenToBazel.HelloWorld.HelloWorldApplication"

)

