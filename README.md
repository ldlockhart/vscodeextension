Hey folks,

Thanks for helping me test out this new VS Code extension for Beefree SDK snippets. This guide will get you up and running locally in a couple of minutes.

---

## Quick Start (Running Locally)

1.  **Clone the Repo:**
    Clone this repository to your local machine.

    git clone https://github.com/ldlockhart/vscodeextension.git


2.  **Install Dependencies:**
    Navigate into the project folder and install the required dependencies as shown

    cd beefree-sdk-snippets
    npm install express joi express-rate-limit node-fetch


3.  **Open in VS Code:**
    Open the entire project folder in Visual Studio Code.
    code .


4.  **Run the Extension:**
    Press **`F5`** (`Run > Start Debugging`). This will compile the extension and launch a new **"Extension Development Host"** window. This new window has the extension installed and ready for testing.

---

## How to Test the Snippets

1.  In the **new** "Extension Development Host" window, create a test file (e.g., `test.js` or `server.js`).
2.  Start typing one of the prefixes from the table below (like `b-init-server`).
3.  You should see the snippet appear in the auto-completion list. Press Enter or Tab to insert it.
4.  Check if the code looks right, the indentation is correct, and you can tab through any placeholders.

---

## Available Snippets

| Prefix          | Description                                         | Language(s) |
| --------------- | --------------------------------------------------- | ----------- |
| `b-init-server` | Node.js/Express server-side authentication endpoint | JS, TS      |
| `b-init-client` | Client-side SDK initialization flow                 | JS, TS      |
| `b-config`      | Standard `beeConfig` object                         | JS, TS      |
| `b-save`        | `onSave` callback function                          | JS, TS      |
| `b-load`        | `bee.load()` method                                 | JS, TS      |
| `b-container`   | HTML `div` container for the editor                 | HTML        |

---

Let me know what you think!
-------------------------------------------------

--- below is rough draft for final publish. WIP ---
Beefree SDK Snippets
Speed up your Beefree SDK integration with this collection of handy code snippets for Visual Studio Code.

This extension provides snippets for common tasks, including the secure server-side authentication flow, client-side initialization, configuration, and more, helping you get up and running with the Beefree email, page, and pop-up builders faster.

Features
This extension provides snippets for JavaScript, TypeScript, and HTML.

Available Snippets
Prefix

Description

b-init-server

Boilerplate for a secure Node.js/Express auth endpoint.

b-init-client

Full client-side initialization flow.

b-config

A standard configuration object for the SDK.

b-save

The onSave callback function.

b-load

The bee.load() method to load a new template.

b-container

The HTML div container for the editor.

How to Use
Simply start typing one of the prefixes (like b-init-server) in a relevant file (.js, .ts, .html) and press Enter or Tab to insert the snippet.

Installation
Install through the Visual Studio Code Marketplace.

Launch VS Code Quick Open (Ctrl+P), paste ext install your-publisher-name.beefree-sdk-snippets, and press enter.

Contributing
Found a bug or have a suggestion? Feel free to open an issue or submit a pull request on our ** Github Repository **

Full Beefree SDK docuentation can be found here: https://docs.beefree.io/beefree-sdk
Enjoy!
