# release-test
This repository will perform testing for the release environment.

## How to use

When you push a tag, GitHub Actions will run.

The tag will become the name of the release. If the application resides under the temp directory, only the application will be archived and uploaded.
## Use package

- [action-gh-release](https://github.com/softprops/action-gh-release)
- [zip-release](https://github.com/thedoctor0/zip-release/tree/0.7.5/?tab=readme-ov-file)