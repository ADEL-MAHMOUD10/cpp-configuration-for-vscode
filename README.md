# C++ Development Environment Setup with MinGW and VS Code

## 1. Download MinGW
Download the MinGW file from [this link](https://www.mediafire.com/file/etqb34ppi6rjt0x/mingw-64.7z/file).

## 2. Extract MinGW
Extract the `mingw-64` folder to your C drive (`C:\`).
![Extraction Example](https://i.postimg.cc/q7YD4HVh/image.png)

## 3. Update Environment Variables
1. Open Windows Settings and search for "Edit environment variables."
2. In the User variables section, select the `Path` variable and click "Edit."
3. Click "New" and add `C:\mingw64\bin`.
   ![Path Update Example](https://i.postimg.cc/brRRGKMR/image-1.png)
4. Click "OK" to save the changes.

## 4. Configure VS Code
1. Create a `.vscode` folder in your project directory.
2. Download the configuration files (`c_cpp_properties.json`, `launch.json`, and `tasks.json`) from:
   - [this direct link](https://www.mediafire.com/file/cs4tw82kn4a5554/configuration.7z/file)
3. or download from this repositorie by:
    ```bash
    git clone https://github.com/adel1046/cpp-configuration-for-vscode.git
    ```

4. Extract these files into the `.vscode` folder in your project directory.
5. If these files already exist in the folder, replace them with the new files.

## 5. Verify Installation
1. Open Command Prompt and write this command `g++ --version` to check if MinGW is installed correctly.
2. If you see information about the `g++` version, MinGW is installed correctly.


