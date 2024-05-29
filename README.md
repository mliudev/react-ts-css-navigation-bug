# react-ts-css-navigation-bug

Demo repo for reproducing a cmd+click navigation bug in VSCode extension `react-ts-css`.

## run dev

```bash
npm i
npm run dev
```

Go to <http://localhost:5170> to observe running server with scss modules compiled and working.

## bug demo

Go to [src/app/layout.scss](src/app/layout.scss) and note that you can't CMD+click into the
[src/app/reset.module.scss](src/app/reset.module.scss) file.

## resources

May be related to:

- https://github.com/microsoft/vscode/issues/163967
