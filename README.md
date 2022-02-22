# GitHub Actions Sandbox

A temporary repository for experimenting with GitHub Actions for JUCE CMake Audio Plugin Template.

## MacOS Build Performance Statistics

Case | Config | # Runs | Average duration
-|-|-|-
A | Xcode, buildcache | 15 | 5m 57s
B | Xcode, ccache | 15 | 7m 16s
C | make -j6, ccache | 15 | 5m 27s

*Note:* GitHub Actions build times on MacOS vary a lot from run to run. To make reasonable conclusions, we need to accumulate statistics (tens of runs).