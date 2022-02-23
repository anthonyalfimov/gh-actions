# GitHub Actions Sandbox

A temporary repository for experimenting with GitHub Actions for JUCE CMake Audio Plugin Template.

## MacOS Build Performance Statistics

Case | Config | # Runs | Average duration
-|-|-|-
A | Xcode, buildcache | 25 | 6m 9s
B | Xcode, ccache | 25 | 7m 18s
C | make -j6, ccache | 25 | 5m 14s

*Note:* GitHub Actions build times on MacOS vary a lot from run to run. To make reasonable conclusions, we need to accumulate statistics (tens of runs).