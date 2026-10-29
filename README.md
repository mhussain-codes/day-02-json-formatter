# JSON Desk — Day 02

A free, local-first JSON formatter for the everyday moments when an API response is hard to read or a payload needs to be compact.

**[Open JSON Desk](https://mhussain-codes.github.io/day-02-json-formatter/)** · [View source](https://github.com/mhussain-codes/day-02-json-formatter)

## What it does

- Formats and minifies valid JSON.
- Shows a clear parser error when the input is invalid.
- Lets you choose two spaces, four spaces, or tabs for indentation.
- Optionally sorts object keys, including nested objects.
- Copies the result or downloads it as `formatted.json`.
- Shows the root type, key count, item count, and output size.
- Supports Ctrl/Cmd + Enter to format.

## Use it

1. Open `index.html` in a modern browser, or use the live link above.
2. Paste a JSON object, array, or primitive into the input panel.
3. Choose **Format JSON** or **Minify**. Use **Copy** or **Download** for the result.

## Privacy

Parsing and formatting run in your browser with the built-in `JSON` API. The page does not send input to a server, use analytics, or store it. Clipboard access happens only after you choose **Copy**; downloads are generated on your device.

## Scope

This tool validates JSON syntax. It does not validate an API schema, check whether values are correct for your application, or detect duplicate object keys. Review sensitive or production data before using the result.

## Built with

HTML, CSS, and vanilla JavaScript. No build step or external dependencies. Licensed under MIT.
