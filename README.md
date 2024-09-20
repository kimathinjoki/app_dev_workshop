# Setting up React on Windows and macOS

This guide will help you set up your environment for React development on Windows and macOS.

## Prerequisites

- Windows 10+ or macOS 10.13+
- Internet connection
- Basic command line knowledge

## Setup Steps

### 1. Install Node.js and npm

#### Windows:
1. Visit https://nodejs.org/
2. Download and install the LTS version
3. Verify installation:
   ```
   node --version
   npm --version
   ```

#### macOS:
1. Install Homebrew:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install Node.js:
   ```
   brew install node
   ```
3. Verify installation:
   ```
   node --version
   npm --version
   ```

### 2. Install a Code Editor

1. Go to https://code.visualstudio.com/
2. Download and install for your OS
3. Open VS Code after installation

### 3. Create a New React Application

1. Open Command Prompt/Terminal
2. Navigate to your project directory
3. Create a new React app:
   ```
   npx create-react-app new-app
   ```
4. Move into the project folder:
   ```
   cd new-app
   ```
5. Start the development server:
   ```
   npm start
   ```

# Create React App Project Structure

After running `create-react-app`, your project structure will look like this:

```
my-react-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
```

## Key Files and Directories

### `README.md`
- This file! It's where you document your project.

### `node_modules/`
- Contains all the project dependencies.
- You shouldn't modify or commit this directory.

### `package.json`
- Lists project dependencies and contains scripts for running, building, and testing your app.

### `public/`
- Contains the public assets of your app.

#### `index.html`
- The main HTML file for your app.
- The entry point for the browser.

### `src/`
- Contains the source code for your React app.

#### `index.js`
- The JavaScript entry point for your app.

#### `App.js`
- The main React component.

#### `App.css`
- Styles for the App component.

#### `App.test.js`
- Test file for the App component.

## Getting Started

1. Navigate to your project directory:
   ```
   cd my-react-app
   ```

2. Start the development server:
   ```
   npm start
   ```

3. Open `src/App.js` to begin editing your app.

4. Install additional npm packages as needed

Happy coding!