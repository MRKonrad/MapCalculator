# Continous Integration Playground

| System        | Status           |
|:-------------:|:-------------:|
| Travis CI     | [![CLang  / GCC / XCode Builds](https://travis-ci.org/MRKonrad/ContinousIntegrationPlayground.svg?branch=master)](https://travis-ci.org/MRKonrad/ContinousIntegrationPlayground) | 
| AppVeyor      | [![Visual Studio Builds](https://ci.appveyor.com/api/projects/status/hmh1bobcjd530td1?svg=true)](https://ci.appveyor.com/project/MRKonrad/continousintegrationplayground) |
| Coveralls     | [![Coverage Status](https://coveralls.io/repos/github/MRKonrad/ContinousIntegrationPlayground/badge.svg?branch=master)](https://coveralls.io/github/MRKonrad/ContinousIntegrationPlayground?branch=master) |

# Inspiration
Based on [this repo](https://github.com/LearningByExample/ModernCppCI) and [this post](http://david-grs.github.io/cpp-clang-travis-cmake-gtest-coveralls-appveyor/).

# Notes

* entries in  `.gitmodules` are added automatically by calling for example  
 `git submodule add https://github.com/google/googletest.git ./thirdParty/googletest`
* to generate coverage `lcov --capture --directory . --output-file coverage.info`
* to generate coverage html report `genhtml coverage.info --output-directory out`


