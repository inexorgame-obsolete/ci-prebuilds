# Inexor's CI Prebuilds

Inexor has many C/C++ dependencies, which we manage with [Conan packages](https://www.conan.io).

This repository uses Conan's Docker containers to compile packages for Linux, Travis macOS environments for macOS packages and AppVeyor's Windows environments for Windows packages.

**Why?**
  * all Inexor team members can trigger a (re-)build easily
  * transparent, reproducible build process
  * easier to debug
  * reduces build time for the majority of developers
  * mass testing of your dependencies

If the builds are successful the binaries will get uploaded to our [Conan repository](https://bintray.com/inexorgame/inexor-conan).
