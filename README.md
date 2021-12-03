# <img src="public/images/logo.svg" height="53" alt="Docassemble Filler" title="Docassemble Filler" />

This extension allows you to fill all form inputs (textboxes, textareas, radio
buttons, dropdowns, etc.) with dummy data. It is a must for developers and
testers who work with forms as it avoids the need for manually entering values
in fields. Based on the extension [Fake
Filler](https://github.com/FakeFiller/fake-filler-extension), updated to work
with [Docassemble](https://docassemble.org) checkboxes and radio buttons.

## Install

This extension is not published yet. You can experiment with it for now by following the developer instructions.

## Default shortcut

Use **_CTRL+SHIFT+F_** on Windows and **_CMD+SHIFT+F_** on Mac to fire the extension. See the [Keyboard Shortcuts](https://github.com/FakeFiller/fake-filler-extension/wiki/Keyboard-Shortcuts) page for more details.

## Developing (in Firefox)

1. `npm install`
1. `npm run build`
1. Follow instructions for [building your first Firefox extension](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
    * In Firefox, open [about:debugging](about:debugging)
    * Click on the link to [this firefox](about:debugging#/runtime/this-firefox) to visit the extensions page
    * Click on "load temporary add-on" and then navigate to the `/dist` folder. Select the `manifest.json` file to load the extension.

### Enable extension debugging

1. open `about:config` in Firefox
1. as a search term, type `extensions.sdk.console.logLevel` and click the `+` button to add a new setting with the type "string".
1. set the value of the new setting to `all`.

### View extension console log

In the [this firefox](about:debugging#/runtime/this-firefox) page, next to the add-on, click the "inspect" button.
