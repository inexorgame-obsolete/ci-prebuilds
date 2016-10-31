# Inexor's CI Prebuilds

Inexor ships a lot of dependencies in a pre-built form in our [platform repository](https://github.com/inexor-game/platform/). While this saves a lot of compile time for the majority of developers it is also a huge burden to maintain.

This repository uses our [Docker builds](https://github.com/inexor-game/ci-docker) to compile our pre-built dependencies on Travis.

**Why?**
 * all Inexor team members can trigger a (re-)build easily
 * transparent, reproducable build process
 * easier to debug
 
If the builds are successfull the binaries will get uploaded to our dependencies server. Inexor team member can then download them, check them out locally and push them to our platform repository if they are fine.
