nunit-distribution ![Appveyor build](https://ci.appveyor.com/api/projects/status/github/nunit/nunit-distribution?branch=master&svg=true)
==================

MSI installer which bundles multiple NUnit 3 components. 

##Building

NUnit uses Cake (http://cakebuild.net) to fetch the assemblies for install, and build the installer. Further information is in [BUILDING.md](BUILDING.md).

##Release

When doing a new version, the following items need to be updated manually:
* Version string in `build.cake`
* Changelog, at `resources/CHANGES.txt`
