use_relative_paths = True

vars = {
  "chromium_url": "https://chromium.googlesource.com",

  "clang_format_rev": "ac00eadce00243bf8734da8d156b8ed19dc37fd3", # r290930
  "libcxx_revision": "b1ece9c037d879843b0b0f5a2802e1e9d443b75a",    # r256621
  "libcxxabi_revision": "0edb61e2e581758fc4cd4cd09fc588b3fc91a653", # r256323
}

deps = {
  "clang_format/script":
    Var("chromium_url") + "/chromium/llvm-project/cfe/tools/clang-format.git@" +
    Var("clang_format_rev"),
  "third_party/libc++/trunk":
    Var("chromium_url") + "/chromium/llvm-project/libcxx.git" + "@" +
    Var("libcxx_revision"),
  "third_party/libc++abi/trunk":
    Var("chromium_url") + "/chromium/llvm-project/libcxxabi.git" + "@" +
    Var("libcxxabi_revision"),
}
