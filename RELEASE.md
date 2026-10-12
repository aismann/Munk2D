This document describes how to do a release of Munk2D.

- [ ] Update or verify the version number in these files:

  - CMakeLists.txt
  - src/CMakeLists.txt
  - include/chipmunk/chipmunk.h
  - CHANGELOG.md

- [ ] Set the actual publication date in CHANGELOG.md.
- [ ] Run the Release test suite with benchmarks enabled, the backend-disabled tests, and sanitizer checks; verify current CI is green.
- [ ] Verify the shared/static install and library version.
- [ ] Commit release metadata, tag the verified commit, and publish the GitHub release.
- [ ] Include numerical compatibility and CPU/workload-dependent AVX2 performance caveats in the release notes.
- [ ] Verify the downloadable tag archive builds and passes tests.
