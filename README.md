<div align="center">

<h1>🚀 Setting up for ITCC App Dev Workshop on Windows and MacOS</h1>

<div id="header">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDB5YzljczBpcWV1Z2kxc3cxdXBveDg2dmc2Y2Q1Ym5pMXc3dHo5NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KEYMsj2LcXzfcTP5ii/giphy.webp" width="100" style="margin: 10px;"/>
</div>

<p><strong>This guide will help you set up your environment for React development on Windows and macOS as preperation of the workshop.</strong></p>

</div>


---

## 📋 Prerequisites

- Working laptop
- Windows 10+ or macOS 10.13+
- Internet connection
- Basic command line knowledge

---

## 🛠️ Setup Steps

### 1. Install Node.js and npm

<details>
<summary>Windows Instructions</summary>

### Accessing the Command Prompt

1. Press `Win + R` to open the Run dialog.
2. Type `cmd` and press `Enter` to open the Command Prompt.

### Accessing PowerShell

1. Press `Win + X` to open the Power User menu.
2. Select `Windows PowerShell` or `Windows PowerShell (Admin)`.
3. If prompted, click `Yes` to allow the PowerShell to make changes to your device.

### Installation Steps

1. Visit [https://nodejs.org/](https://nodejs.org/)
2. Download and install the LTS version.

### Alternative: Using PowerShell or Command Prompt

1. Open PowerShell or Command Prompt.
2. Check the current execution policy:
    ```powershell
    Get-ExecutionPolicy
    ```
    - If the output is `Restricted`, then set the execution policy to `AllSigned`:
    ```powershell
    Set-ExecutionPolicy AllSigned
    ```
    - You will be prompted to confirm the change. Type `A` and press `Enter` to confirm.
3. Install Chocolatey (a package manager for Windows):
    ```powershell
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    ```
4. Use Chocolatey to install Node.js:
    ```
    choco install -y --force nodejs-lts
    ```
### Verify installation:
    ```
    node --version
    npm --version
    ```
</details>

<details>
<summary>macOS Instructions</summary>

### Accessing the Terminal

1. Open Finder.
2. Navigate to the `Applications` folder.
3. Open the `Utilities` folder.
4. Double-click on `Terminal` to open it.

### Installation Steps

1. Install Homebrew:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install Node.js:
   ```bash
   brew install node
   ```
3. Verify installation:
   ```bash
   node --version
   npm --version
   ```
</details>

### 2. Install a Code Editor

1. Go to [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Download and install for your OS
3. Open VS Code after installation


<div align="center"> 
📫 Have any questions? Please reach out:
    <a href="mailto:kfnchx@umsl.edu">
    <img src="https://cdn-icons-png.flaticon.com/512/552/552486.png" width="28" height="28" style="vertical-align: middle;"/>
  </a>
</div>

<div align="center">
  <h2>🎉 Happy coding! 🎉</h2>
</div>

---