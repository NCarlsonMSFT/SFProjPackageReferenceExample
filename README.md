# Package Reference Example
While using PackageReference in an .sfproj is not officially supported, it is possible. This repo is an example of the changes needed in a .sfproj to add support for using a PackageReference.

The commit: [Change .sfproj to use PackageReference (abd4b7b)](https://github.com/NCarlsonMSFT/SFProjPackageReferenceExample/commit/abd4b7b837a84471dfcc8c9fcfcf5bc022fa1257) contains the tweaks that were needed.

## Notes:
* After restoring the project in VS it needs to be reloaded
* This has been tested in VS 2022 17.7 and 17.8 Preview 1
