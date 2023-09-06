A sample Flutter web project for using on GitHub Codespaces.

In order to use debugging, you'll need to use Chrome with the [Dart Debug extension](https://chrome.google.com/webstore/detail/dart-debug-extension/eljbmlghnomdjgdjmbdekegdkbabckhm?hl=en) installed.

// TODO(dantup): This does not work because of proxy/authentication issues:

Access to fetch at 'https://improved-garbanzo-abcdefghijkl-40019.app.github.dev/$dwdsExtensionAuthentication' from origin 'chrome-extension://eljbmlghnomdjgdjmbdekegdkbabckhm' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource. If an opaque response serves your needs, set the request's mode to 'no-cors' to fetch the resource with CORS disabled.

- Fork this repo
- Open your fork on github.com
- Click the green "Code" button and then "Create Codespace"
- Wait for the Codespace to be created and open the VS Code web editor
- When prompted, click "Run pub get"
- Ensure the "Web Server" is selected in the status bar
- Press `F5` to start launching the app
- If you see "Popup Blocked" in the Chrome address bar, click the notification then on the link to open the page manually
- Click on the Dart Debug Extension icon
- Wait for the "Autentication Success" page, then close that tab
- Reload the app page (?)
- Click on the Dart Debug Extension icon again
