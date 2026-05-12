# Custom Bootstrapper for demonstrating a cancel problem in Burn

The project contains a custom bootstrapper and 4 msi packages. The three last packages are non-vital, and if the installation is cancelled during one of those, the installation will not roll back.

If the last package is changed to be vital, the installation will roll back if the installation is cancelled during one of the non-vital packages.