# GitHub Actions Sandbox

A temporary repository for experimenting with GitHub Actions for JUCE CMake Audio Plugin Template.

## MacOS Build Performance Statistics

Case | Config | # Runs | Average duration
-|-|-|-
A | Xcode, buildcache | 30 | 6m 14s
B | Xcode, ccache | 30 | 7m 15s
C | make -j6, ccache | 30 | 5m 9s

*Note:* GitHub Actions build times on MacOS vary a lot from run to run. To make reasonable conclusions, we need to accumulate statistics (tens of runs).
