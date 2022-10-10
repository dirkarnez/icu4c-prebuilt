icu4c-prebuilt
==============
Prebuilt of [icu/icu4c at main · unicode-org/icu](https://github.com/unicode-org/icu/tree/main/icu4c)

### TODOs
- ~~fix no data is in the `libsicudt.a`~~
  - fixed: to have language data generated and copied to installation directory, both static and shared are needed to be built - since icu tools requires shared library to compile

### Notes
- Windows build with flag `--enable-auto-cleanup` and without further configuration cause "multiple `DllMain` found error"

### Playground
- [dirkarnez/icu4c-playground](https://github.com/dirkarnez/icu4c-playground)

### Reference
- [LibCMaker/ICU_CMake_Files: ICU build files for CMake build tools.](https://github.com/LibCMaker/ICU_CMake_Files)
- [ICU Documentation - ICU Documentation](https://unicode-org.github.io/icu/)
