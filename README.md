### Requirements
- VcPkg must be locally available (https://github.com/microsoft/vcpkg)
- environment variable VCPKG_ROOT must be set to the root of VcPkg containing vcpkg.exe
- Visual Studio 2022 must be installed
- VcPkg-handling for Visual Studio 2022 must be installed, execute the following command to install
  `"%VCPKG_ROOT%\vcpkg.exe" integrate install`
### Build sample using Visual Studio 2022
- open `msbuild.sln` in Visual Studio 2022
- now you can build project using your IDE
