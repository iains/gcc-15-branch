# This is a branch of GCC-15.3 supporting AArch64(Arm64) on Darwin.

The branch is suitable for i686, x86_64 and aarch64 Darwin from Darwin9 (MacOSX 10.5) through Darwin23 (macOS 14 / Sonoma) on architectures relevant to each version.  It should also be applicable to powerpc but has not been tested there.

Please see README for general information on the GCC sources

The GCC 15.3 upstream release has many changes and improvements, please see the general GCC release documentation for details.

Please see gcc/config/aarch64/darwinpcs.md for a description of the AArch64 ABI
support.

**_The current release is GCC-15.3-darwin-r0. (June 2026)_**

In addition to the AArch64 support, this release:

 * Contains a number of fixes for compatibility with newer Xcode tools
 * Contains a number of fixes for compatibility with newer SDKs.
 * Adds support for a number of clang extensions that have been used in various SDK versions.

Extras thanks to:
 * 'FX' (https://github.com/fxcoudert) for the main part of the ```__float128``` support, progressing upstream commits and test fixes.

Iain Sandoe, June 2026.

Please report issues for this branch to:
https://github.com/iains/gcc-15-branch/issues
