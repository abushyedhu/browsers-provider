# testcafe-browser-provider-plugin

This browser plugin provides following browsers to TestCafe tool when [playwright](https://www.npmjs.com/package/playwright) is installed:

- `chromium`
- `chromium:headless`
- `firefox`
- `firefox:headless`
- `webkit`
- `webkit:headless`

It also supports mobile device emulation (only with `chromium` and `webkit` engines).

here's command to view all available browser aliases by running on locally:

```
testcafe -b plugin
```

Package can be installed from [npm](https://www.npmjs.com/package/testcafe-browser-provider-plugin):

```
npm install playwright --save-dev
npm install testcafe-browser-provider-plugin --save-dev
```
