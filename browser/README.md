
# Stealth Browser

The Stealth Browser is a Browser UI which is implemented using
Web Technologies, so that it is possible to change the Browser
Engine or Web View easily.


## URL-Parameter Flags

- `/browser/index.html?debug=true` is a parameter to toggle
   loading/debugging of the UI by disabling the Service Worker.
   The default value is `false`.


## Quickstart

- Install [node.js](https://nodejs.org/en/download) version `10+`.
- Install [Ungoogled Chromium](https://github.com/Eloston/ungoogled-chromium/releases) version `70+`.

```bash
cd /path/to/stealth;

# Start Stealth Service
node ./stealth/stealth.mjs;

# Open Browser Progressive Web App
node ./browser/browser.mjs;

# Open in other (modern) Web Browser
# gio open http://localhost:65432;
```

