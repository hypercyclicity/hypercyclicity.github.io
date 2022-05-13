This page is loaded when opening a new tab (C-t) in the browser.

In Chrome, we're using New Tab Redirect:
https://github.com/jimschubert/newtab-redirect

To generate the CSS with Tailwind styles we're using:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch --minify
```
