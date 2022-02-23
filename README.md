# GitHub Actions Sandbox

A temporary repository for experimenting with GitHub Actions for JUCE CMake Audio Plugin Template.

## MacOS Build Performance Statistics

Case | Config | # Runs | Average duration
-|-|-|-
A | Xcode, buildcache | 20 | 6m 10s
B | Xcode, ccache | 20 | 7m 42s
C | make -j6, ccache | 20 | 5m 16s

*Note:* GitHub Actions build times on MacOS vary a lot from run to run. To make reasonable conclusions, we need to accumulate statistics (tens of runs).