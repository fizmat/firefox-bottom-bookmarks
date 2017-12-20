# firefox-bottom-bookmarks
While we're waiting for WebExtensions to add toolbar support, why not just put bookmarks at the bottom?

## Why

Some people prefer to have a statusbar at the bottom and put addon icons on it. I liked [Extended Statsubar](https://github.com/kustodian/extended-statusbar). Firefox 57 has no toolbar API, so all toolbar-based addons broke.

What it get you is a place to put extra addon icons, for example:
![Firefox with addons on the bookmark bar screenshot](https://i.imgur.com/qNQRP19.png)

## How
Inspired by this [discussion on Mozilla Support about putting tabs at the bottom of the page](https://support.mozilla.org/en-US/questions/1189624).

While [userChrome.css lacks up-to-date documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Tech/XUL/Tutorial/Modifying_the_Default_Skin), this snippet should not break anything.

Just put it in your firefox profile/chrome/userChrome.css

## Why not

This is a minimalist hack, but I need it for now.

This is obsoleted if/when [Firefox implements toolbar API](https://bugzilla.mozilla.org/show_bug.cgi?id=1215064)
