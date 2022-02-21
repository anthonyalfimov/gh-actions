# GitHub Actions Sandbox

A temporary repository for experimenting with GitHub Actions for JUCE CMake Audio Plugin Template.

## MacOS Build Performance Statistics

Case | Config | # Runs | Average duration
-|-|-|-
A | Xcode, buildcache | 5 | 5m 53s
B | Xcode, ccache | 5 | 5m 37s
C | make, ccache | 5 | 4m 12s

*Note:* GitHub Actions build times on MacOS vary a lot from run to run. To make reasonable conclusions, we need to accumulate statistics (tens of runs).