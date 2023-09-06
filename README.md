A sample Flutter web project for using on GitHub Codespaces.

In order to use debugging, you'll need to use Chrome with the [Dart Debug extension](https://chrome.google.com/webstore/detail/dart-debug-extension/eljbmlghnomdjgdjmbdekegdkbabckhm?hl=en) installed.

**This currently only works if the exposed ports are made Public. Use this at your own risk!**

- Ensure `[*.]github.dev` is allowed to open popups in Chrome
- Fork this repo
- Open your fork on github.com
- Click the green "Code" button and then "Create Codespace"
- Wait for the Codespace to be created and open the VS Code web editor
- When prompted, click "Run pub get"
- Ensure the "Web Server" is selected in the status bar
- Press `F5` to start launching the app
- Wait for the new tab to spawn to run the app and drag the tab out into its own window
- Switch back to the VS Code editor tab and under Ports make the exposed ports public
- Switch back to the app tab
- Reload the page and wait for the Dart Debug Extension icon to turn blue
- Click on the Dart Debug Extension icon

