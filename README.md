This is a fork of [OsaSoft/Youtube better subscriptions](https://github.com/OsaSoft/youtube-better-subscriptions), updated to Manifest V3, to make it work in Chrome 138+ (as per https://github.com/OsaSoft/youtube-better-subscriptions/issues/195).

**Important note:** this does not remember any videos you watched with the original Youtube Better Subscriptions. At least with Chrome 138 and 139, [it's possible](https://www.neowin.net/guides/you-can-still-enable-ublock-origin-in-chrome-here-is-how/) to temporarily re-enable Manifest V2 extensions like YBS, so you can export your watched videos from there, and then import them with this fixed version. I don't have any advice to restore your watched videos if that doesn't work or stops working.

This fix is not available in the Chrome store. It can be added to the browser by downloading the code and following the instructions to "Load an unpacked extension" in [the Chrome documentation](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked).

Use at your own risk. I've been happily using Youtube Better Subscriptions for a while now, but I can't guarantee its safety.

This is not intended to meaningfully extend the original project, nor fix any future issues. I'll probably take a look at pull requests to fix minor issues that stop this from working. But if you're interested in making bigger changes, you're better off creating your own branch.

The original readme follows below.

---

# Youtube better subscriptions
This plugin aims to make navigating YouTube's subscription grid easier by allowing users to hide watched videos.
This plugin is in early development and will often change and (hopefully) include new features.

Available for Firefox: https://addons.mozilla.org/cs/firefox/addon/youtube-better-subscriptions/

Available for Chrome: https://chrome.google.com/webstore/detail/better-subscriptions-for/fkchdogohkjpnhfkganifkbbjcjofbjf


The icon for the marked watched Button is based on: https://commons.wikimedia.org/wiki/File:OOjs_UI_icon_eye.svg published under the CC-BY-SA-3.0, the modified version is licensed under CC-BY-SA-4.0

The icon for the settings Button is taken based on: https://commons.wikimedia.org/wiki/File:OOjs_UI_icon_settings.svg published under the MIT licence, , the modified version is licensed under MIT

The addon as a whole is still licensed under the GPLv3

## Contribution guidelines
- Please follow code style conventions set across the project. Ie, use `let` instead of `var`, use proper opening and closing curly braces for `if`s, etc
  - If your IDE doesnt automatically apply settings from .editorconfig, please take care that you indent using spaces, not tabs.
- Branch off and create Pull Requests from the master branch
