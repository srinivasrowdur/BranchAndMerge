fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios oncommit

```sh
[bundle exec] fastlane ios oncommit
```

Run Tests & Increase Build number

### ios onpatchmerge

```sh
[bundle exec] fastlane ios onpatchmerge
```

Run Tests & Increase Build number and update patch version number

### ios onminormerge

```sh
[bundle exec] fastlane ios onminormerge
```

Run Tests & Increase Build number and update Minor version number

### ios onmajormerge

```sh
[bundle exec] fastlane ios onmajormerge
```

Run Tests & Increase Build number and update Major version number

### ios incrementpatch

```sh
[bundle exec] fastlane ios incrementpatch
```

Increment patch version

### ios incrementminor

```sh
[bundle exec] fastlane ios incrementminor
```

Increment minor version

### ios incrementmajor

```sh
[bundle exec] fastlane ios incrementmajor
```

Increment Major version

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
