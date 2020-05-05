load(
    "@bazelruby_rules_ruby//ruby:defs.bzl",
    "ruby_binary",
    "ruby_library",
)

cc_binary(
  name = "ex",
  srcs = ["ex.c"],
  visibility = ["//visibility:public"],
)

ruby_binary(
  name = "gen",
  srcs = ["gen.rb"],
  visibility = ["//visibility:public"],
  data = ["package.erb", "target.erb"],
)

