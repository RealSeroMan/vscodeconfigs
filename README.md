# vscodeconfigs

## Introduction
This repository contains ready-to-use Visual Studio Code configuration templates specifically designed for C/C++ development environments using GCC, GDB, and G++. It includes separate setup files for GCC and G++ to ensure that developers can quickly configure their projects according to their specific needs.

## Update
tasks.json and launch.json files for java language has been added. In the java_setup_multiple_sources directory, you can get the tasks.json and launch.json files for multiple source files. It will automatically detect the files in the src directory, and generator .class files into the bin directory. You can change the directory names yourselves.

## Repository Structure
- **gcc_setup/**: Contains configuration files for C programming with GCC.
  - `c_cpp_properties.json`: Compiler path and IntelliSense configurations.
  - `launch.json`: Debugger configuration settings.
  - `tasks.json`: Build tasks for compiling C programs.
  - `settings.json`: VSCode settings for C development.
- **gpp_setup/**: Contains configuration files for C++ programming with G++.
  - `c_cpp_properties.json`: Compiler path and IntelliSense configurations.
  - `launch.json`: Debugger configuration settings.
  - `tasks.json`: Build tasks for compiling C++ programs.
  - `settings.json`: VSCode settings for C++ development.
- **LICENSE**: The MIT License under which this repository is made available.
- **README.md**: This file, which provides an overview and setup instructions.

## Setup Instructions
To use these templates in your VSCode environment, follow these detailed steps:

### Configuring Compiler and IntelliSense Settings
1. **Open Command Palette**: Use `Ctrl+Shift+P` in VSCode.
2. **Access Configuration**: Type `C/C++: Edit Configurations (UI)` and select it.
3. **Use the UI to Configure**: Use the Visual Studio Code UI to set the compiler path and IntelliSense settings as per your environment. You do not need to manually copy anything for these settings; the UI is designed to generate and update the `c_cpp_properties.json` as needed.

### Setting Up Build Tasks and Debug Configuration
The `tasks.json` and `launch.json` files contain custom settings that need to be manually copied:
1. **Navigate to either `gcc_setup` or `gpp_setup` folder** depending on your development preference.
2. **Copy the contents** of `tasks.json` and `launch.json`.
3. **Paste these contents** in the corresponding files under the `.vscode` folder of your working project in VSCode.

### Additional VSCode Settings
- For further customization such as formatting and editor preferences, you can manually copy the contents of `settings.json` from the respective directory (`gcc_setup` or `gpp_setup`) to your workspace settings in VSCode.

## Contributing
Contributions to this repository are welcome. Please feel free to fork, modify, and submit pull requests to enhance the configurations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
