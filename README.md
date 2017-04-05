# conan_workshop
Workshop using conan.io for the C++ Usergroup Zentralschweiz Meeting

Please refer to the conan.io documentation if you need detailed help: http://docs.conan.io/en/latest/

# Exercises

## conanfile.txt
1. Try to build the project

    ```
    #>mkdir build && cd build && cmake ..
    #>make
    ```
2. Create a ```conanfile.txt``` to define the dependencies
3. Use ```conan install``` to install the dependencies
4. Modify ```CMakeLists.txt``` to use the conan settings
5. Build the project again (See step 1.)

## Build with options and settings

1. Check the package documentations for possible options and try to set some for your project
2. If you have multiple compilers or compiler versions or different libstd version installed, try to build your project with different settings

## Profiles
1. If you have multiple compilers or compiler versions or different libstd version installed, try to create and use profiles to build your project for the different settings.

## conanfile.py
1. Write a ```conanfile.py``` to build your project, i.e. that you can use ```conan build``` to build your project instead of the commands used above.

## Create your own package
1. Create a conanfile.py which builds and packages your project or
2. create a package from a library of your choice, e.g. the Igloo test framework.
3. Create a testpackage which uses your library and is used to test your package.
