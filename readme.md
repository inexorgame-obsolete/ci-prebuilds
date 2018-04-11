# Inexor's CI Prebuilds

Inexor has many C++ dependencies, which we manage with [Conan packages](https://www.conan.io).

This repository uses our [Docker containers](https://github.com/inexorgame/ci-docker) to compile our C++ dependencies on Travis and AppVeyor.

**Why?**
  * all Inexor team members can trigger a (re-)build easily
  * transparent, reproducible build process
  * easier to debug
  * reduces build time for the majority of developers
  * mass testing of your dependencies

If the builds are successful the binaries will get uploaded to our [Conan repository](https://bintray.com/inexorgame/inexor-conan).
