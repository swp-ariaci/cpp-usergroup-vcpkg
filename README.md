### Requirements
- at least CMake 3.25 must be locally available (https://cmake.org)
- VcPkg must be locally available (https://github.com/microsoft/vcpkg)
- environment variable VCPKG_ROOT must be set to the root of VcPkg containing vcpkg.exe
### Build sample using CMake (Visual Studio 2022, x64)
To build this sample using CMake at command line run the following command:

`cmake -G "Visual Studio 17 2022" --toolchain "%VCPKG_ROOT%/scripts/buildsystems/vcpkg.cmake" -A x64 -B ./build/x64`
