<div align="center">

# 🚀 Setting up React on Windows and macOS

<div id="header">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDB5YzljczBpcWV1Z2kxc3cxdXBveDg2dmc2Y2Q1Ym5pMXc3dHo5NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KEYMsj2LcXzfcTP5ii/giphy.webp" width="100" style="margin: 10px;"/>
</div>

This guide will help you set up your environment for React development on Windows and macOS.

</div>


---

## 📋 Prerequisites

- Windows 10+ or macOS 10.13+
- Internet connection
- Basic command line knowledge

---

## 🛠️ Setup Steps

### 1. Install Node.js and npm

<details>
<summary>Windows Instructions</summary>

1. Visit [https://nodejs.org/](https://nodejs.org/)
2. Download and install the LTS version
3. Verify installation:
   ```bash
   node --version
   npm --version
   ```
</details>

<details>
<summary>macOS Instructions</summary>

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

### 3. Create a New React Application

1. Open Command Prompt/Terminal
2. Navigate to your project directory
3. Create a new React app:
   ```bash
   npx create-react-app new-app
   ```
4. Move into the project folder:
   ```bash
   cd new-app
   ```
5. Start the development server:
   ```bash
   npm start
   ```
6. Open `src/App.js` to begin editing your app.
7. Install additional npm packages as needed

---

## 📁 Create React App Project Structure

After running `create-react-app`, your project structure will look like this:

```
new-app/
├── README.md
├── node_modules/
├── package.json
├── public/
│   ├── index.html
│   └── favicon.ico
└── src/
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    └── logo.svg
```

### Key Files and Directories

| File/Directory | Description |
|----------------|-------------|
| `README.md` | Project documentation |
| `node_modules/` | Contains all project dependencies (don't modify or commit) |
| `package.json` | Lists project dependencies and scripts |
| `public/` | Contains public assets |
| `public/index.html` | Main HTML file, entry point for the browser |
| `src/` | Contains the React source code |
| `src/index.js` | JavaScript entry point |
| `src/App.js` | Main React component |
| `src/App.css` | Styles for the App component |
| `src/App.test.js` | Test file for the App component |

---


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