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
| `b-init-client` | Client-side SDK initialization flow                  | JS, TS      |
| `b-config`      | Standard `beeConfig` object                           | JS, TS      |
| `b-config-multitenant` | Multi-tenant config                            | JS, TS      |
| `b-save`        | `onSave` callback function                          | JS, TS      |
| `b-load`        | `bee.load()` method                                 | JS, TS      |
| `b-load-db`     | Load saved template from backend                    | JS, TS      |
| `b-container`   | HTML `div` container for the editor                 | HTML        |
