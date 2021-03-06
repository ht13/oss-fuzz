# oss-fuzz 

> Fuzzing Open Source Software. 

*Project Status*: We are preparing the project for the first public release. Documentation and smoothing the process is our main priority.

[Open new issue](https://github.com/google/oss-fuzz/issues/new) for questions or feedback.

## Documentation

* [New Library Guide](docs/new_library.md) walks through steps necessary to add fuzzers to an open source project.
* [Running and Building Fuzzers](docs/building_running_fuzzers.md) documents the process for fuzzers that are
  *part of target project* source code repository.
* [Running and Building External Fuzzers](docs/building_running_fuzzers_external.md) documents the process for fuzzers that are
  *part of oss-fuzz* source code repository.
* [Project List](docs/projects.md) lists OSS projects integrated with oss-fuzz.
* [Life of a bug](docs/life_of_a_bug.md)
* [Chrome's Efficient Fuzzer Guide](https://chromium.googlesource.com/chromium/src/testing/libfuzzer/+/HEAD/efficient_fuzzer.md) 
  while contains some chrome-specifics, is an excellent documentation on making your fuzzer better.
* [Guided in-process fuzzing of Chrome components](https://security.googleblog.com/2016/08/guided-in-process-fuzzing-of-chrome.html) -
  Google Security Blog post describing the precursor work we've been doing in Chrome. 

## Build status
[Build status](https://oss-fuzz-build-logs.storage.googleapis.com/status.html)

## Bounties

* freetype2: 
[9](https://bugs.chromium.org/p/oss-fuzz/issues/detail?id=9&can=1&q=&colspec=ID%20Type%20Component%20Status%20Priority%20Milestone%20Owner%20Summary), 
[10](https://bugs.chromium.org/p/oss-fuzz/issues/detail?id=10&can=1&q=&colspec=ID%20Type%20Component%20Status%20Priority%20Milestone%20Owner%20Summary),
[36](https://bugs.chromium.org/p/oss-fuzz/issues/detail?id=36&can=1&q=&colspec=ID%20Type%20Component%20Status%20Priority%20Milestone%20Owner%20Summary)


## References
* [libFuzzer documentation](http://libfuzzer.info)
* [libFuzzer tutorial](http://tutorial.libfuzzer.info)
* [Chromium Fuzzing Page](https://chromium.googlesource.com/chromium/src/testing/libfuzzer/)

