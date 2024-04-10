# pwa-text-editor

## Description

Super Text Editor is a Progressive Web Application (PWA) that enables users to create, edit, and store text documents seamlessly. It provides offline functionality, allowing users to work even without an active internet connection. The integrated service worker and Cache API ensure the application's reliability and availability, even in offline mode. Super Text Editor ensures users can access their documents whenever they need them, regardless of their internet connectivity.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)

## Installation

To set up Super Text Editor, follow these steps:

* Clone the repository to your local machine.

* Navigate to the project directory.

* Install Node.js if you haven't already.

* Run `npm install` to install the required dependencies.

* Ensure you have the following npm packages installed:
  - Express.js: `npm install express`
  - Webpack: `npm install --save-dev webpack`
  - Webpack Dev Server: `npm install webpack-dev-server --save-dev`
  - WebpackPwaManifest: `npm install --save-dev webpack-pwa-manifest`
  - Babel: `npm install babel`
  - CSS Loader: `npm install --save-dev css-loader`
  - Concurrently: `npm install concurrently --save`
  - IndexedDB: `npm install idb`

* After installing the packages, run `npm run install` to install the required modules.

## Usage

Below are some usage instructions for Super Text Editor:

1. **Folder Structure**:
   When you open the application in your editor, you should see a structured folder setup like the one shown below:

   ![Folder Structure](/path/to/folder-structure.png)

2. **Running the Application**:
   Run `npm run start` from the root directory to start the backend and serve the client. This will also bundle your JavaScript files using Webpack. You should see the generated HTML, service worker, and manifest file.

   ![Running the Application](/path/to/run-application.png)

3. **Next-gen JavaScript**:
   The application supports next-gen JavaScript, ensuring that the text editor functions smoothly without errors.

   ![Text Editor](/path/to/text-editor.png)

4. **IndexedDB Integration**:
   IndexedDB immediately creates a database storage upon opening the text editor. Content entered in the editor is saved to IndexedDB and retrieved seamlessly when reopening the application.

   ![IndexedDB Integration](/path/to/indexeddb.png)

5. **Install as Desktop App**:
   Clicking on the Install button allows you to download the web application as an icon on your desktop for easy access.

   ![Desktop Icon](/path/to/desktop-icon.png)

6. **Service Worker and Workbox**:
   Super Text Editor registers a service worker and pre-caches static assets upon loading, ensuring fast performance and offline accessibility.

   ![Service Worker](/path/to/service-worker.png)

   ## Screenshot
   ![Site](./Screenshot%202024-03-04%20at%202.15.43%20PM%20(2).png)

   ## Live Link
   [Live Link](https://pwa-text-editor-f39y.onrender.com)