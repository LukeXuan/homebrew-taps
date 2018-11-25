# Why this repo?

Because now the core tap of homebrew provides only llvm with `--with-toolchain` enabled. Furthermore, they do not provide an option to disable it, as documented in this pull request [#34419](https://github.com/Homebrew/homebrew-core/pull/34419) and this issue [#31510](https://github.com/Homebrew/homebrew-core/issues/31510). This is obviously catastrophic for any user who don't want XCode installed.
