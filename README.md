# 🔥 Visual Studio Code (VS Code) IDE Installation Guideline

Visual Studio Code (VS Code) is used as the Integrated Development Environment (IDE) for software & application development.

> <b>Note</b> : <span style="color: #FF9A23">This document is subject to be refactored/updated based on the technical documentation of the specific tools/packages/operating systems.</span>

### 👉🏻 For Windows OS Users

1. Visit [Visual Studio Code Official Website](https://code.visualstudio.com/)

2. Click on **`Download for Windows`** Button

3. Once the download is completed, run the Windows Installer `.exe`

4. During the installation process, you will be prompted with options. Make sure to check the box ✅ **Add to PATH** before proceeding with the the installation.

5. Follow the Installation Wizard Instructions

6. After the installation is completed, restarting the computer may be needed

### 👉🏻 For MacOS Users

1. Visit [Visual Studio Code Official Website](https://code.visualstudio.com/)

![Visual Studio Code Official Website](/images/vscode.png)

2. Click on **`Download Mac Universal`** Button

3. Once the download is completed, open the downloaded `.dmg` File

4. Drag the Visual Studio Code Icon to the `Applications` Folder

5. Open Visual Studio Code (VS Code) from the `Applications` Folder

### 👉🏻 For Linux OS Users

The installation process varies depending on the Linux Distribution. Below are general instructions for some popular package managers.

### <b>Debian/Ubuntu Based Systems</b>

1. Visit [Visual Studio Code Official Website](https://code.visualstudio.com/)

2. Click on **`Download for Linux`** Button and select the `.deb` Package

3. Open a terminal

4. Navigate to the directory where the downloaded `.deb` file is located

5. Run the following command : 

```sh
sudo dpkg -i <package-file-name>.deb
```

6. If there are missing dependencies, run the following command : 

```sh
sudo apt-get install -f
```

### <b>Red Hat/Fedora Based Systems</b>

1. Visit [Visual Studio Code Official Website](https://code.visualstudio.com/)

2. Click on **`Download for Linux`** Button and select the `.rpm` Package

3. Open a terminal

4. Navigate to the directory where the downloaded `.rpm` file is located

5. Run the following command : 

```sh
sudo dnf install <package-file-name>.rpm
```

## ✅ Open Visual Studio Code (VS Code) from Terminal/Command Prompt

For any Operating Systems (Windows OS, MacOS, Linux OS), do the following to open Visual Studio Code (VS Code) from Terminal or Command Prompt.

1. Open the Terminal / Command Prompt

2. Type `code .` and press <kbd>Enter</kbd> to open Visual Studio Code (VS Code) in the current directory