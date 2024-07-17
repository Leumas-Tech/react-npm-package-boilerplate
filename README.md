# React NPM Boilerplate

Welcome to the React NPM Boilerplate project! This repository serves as a starting point for creating new NPM packages for React. It includes all the necessary setup and configuration to get you started quickly.

## Features

- **Babel**: Pre-configured to transpile modern JavaScript and JSX.
- **Package.json**: Ready to be edited with your package details.
- **Simple Structure**: Just add your files to the `src` folder and update `index.js`.

## Getting Started

### Prerequisites

- Node.js
- NPM

### Clone the Repository

```bash
git clone https://github.com/yourusername/react-npm-boilerplate.git
cd react-npm-boilerplate
```

### Project Structure 

```
react-npm-boilerplate
│
├── src
│   └── App.js
│
├── index.js
├── package.json
├── .babelrc
├── .gitignore
└── README.md
```

### Example index.js
When you clone this boilerplate, this is the only file that needs to be updated.

```
// index.js

// When this boilerplate is cloned, this is the only file that needs to be updated really

// import DynamicComponentLoader from './src/LeumasReactLibrary';
// export default DynamicComponentLoader;

import App from "./src/App";
export default App;

// We basically need an import to fetch the component from the src folder, and then the ability for us to export it from here as well.
```


### Usage
Add your files: Place your React components in the src folder.
Update index.js: Import and export your main component in index.js.


### Build and Publish
To build and publish your NPM package, follow these steps:

### Build the package:

```bash
npm run build
```

### Login to NPM : 
```bash
npm login
```

### Publish the package
```bash
npm publish
```
or 
```bash
npm publish --access restricted
```

