# Cursor-Blink
Simple Chrome extension in order to remove cursor blink in Google Docs (which is not covered by the cursor blink animation default in Windows 10 machines).

Chrome utilizes a class named *kix-cursor* which dictates the cursor blink rate. By setting the animation to 0 and ensuring that it is set as !important, cursor blink rate is eliminated. Some other websites such as the W3Schools code editor use the class *CodeMirror-cursor* from *CodeMirror*, a text editor, and by setting the blink rate to 0 and making the cursor visible, blink rate is eliminated on those pages as well. 

**TO-DO:** Utilize JavaScript to eliminate cursor blink from all webpages in Chrome as well as the Chrome Omnibox.  

Extension on Chrome Web Store:

```https://chrome.google.com/webstore/detail/remove-blink/fnaaokkdhakddpnkbmghogjelkakgpkg?hl=en```
