# vue-detect-browser
Plugin for Vue3 that detects browser name, version, and user-agent

## Installation

```bash
npm i vue-detect-browser
```

In your `main.js:`

```bash
import detectBrowser from "vue-detect-browser";
app.use(detectBrowser);
```
## Usage

### Browser

In any component file it is available as detectBrowser data property

```bash
this.detectBrowser.isChrome
this.detectBrowser.isFirefox
this.detectBrowser.isOpera
this.detectBrowser.isSafari
this.detectBrowser.isEdge
this.detectBrowser.isChromeIOS
this.detectBrowser.isIOS
this.detectBrowser.isIE
```
