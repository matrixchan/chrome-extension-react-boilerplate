# React Chrome Extension Boilerplate

This boilerplate is designed to kickstart your Chrome Extension development using React and TypeScript. With a simplified Webpack build process, you can quickly move from concept to production.

Inspired by [JasonXian's project](https://github.com/JasonXian/react-chrome-extension-boilerplate).

## Getting Started

To set up your development environment and start coding, follow these steps:

1. Run `npm i` to install dependencies.
2. Execute `npm start` to initiate a rapid development mode Webpack build that compiles files into the `dist` folder.
3. Install new packages as needed with `npm i --save-dev <package_name>`.

## Loading The Chrome Extension

To test your Chrome Extension in development mode:

1. Open Chrome and go to `chrome://extensions/`.
2. Enable `Developer mode` in the top right corner.
3. Click on `Load unpacked`.
4. Choose the `dist` folder where your compiled extension resides.

## Production Build

To prepare your extension for production:

1. Use `npm run build` to create an optimized production build in the `dist` folder.
2. Compress the `dist` folder into a ZIP file (e.g., `dist.zip`).
3. Upload the ZIP file to the Chrome Web Store Developer Dashboard for publishing.

## Initial Steps

Get your project repository set up and customize the essential configuration files:

1. Initialize a new git repository with `git init` and commit the default files.
2. Personalize `package.json` with your `author`, `version`, `name`, and `description`.
3. Modify `manifest.json`, ensuring correct `version`, `name`, and `description`.
4. Amend `webpack.common.js`, particularly the title in the `getHtmlPlugins` function to reflect your extension's name.
