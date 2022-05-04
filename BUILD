load("@build_bazel_rules_android//android:rules.bzl", "android_library")

android_binary(
  name = "markers",
  srcs = glob(["src/**/*.java"]),
  custom_package = "com.google.android.apps.markers",
  manifest = "AndroidManifest.xml",
  deps = [
    ":resources",
  ],
)

android_library(
  name = "resources",
  manifest = "AndroidManifest.xml",
  custom_package = "org.dsandler.apps.markers",
  resource_files = glob(["res/**"]),
)
