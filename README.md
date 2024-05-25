# browsers-plugin

This plugin provides following browsers to TestCafe tool when [playwright](https://www.npmjs.com/package/playwright) is installed:

- `chromium`
- `chromium:headless`
- `firefox`
- `firefox:headless`
- `webkit`
- `webkit:headless`

It also supports mobile device emulation (only with `chromium` and `webkit` engines).

You can see all available browser aliases by running:

```
testcafe -b playwright
```


## install

Package can be installed from [npm](https://www.npmjs.com/package/browsers-plugin):

```
npm install playwright --save-dev
npm install browsers-plugin --save-dev
```
