Fork of https://www.npmjs.com/package/react-devtools-electron.

Important changes:

- You must now explicitly add the extension. Example:
  ```typescript
  app.on('ready', () => {
  	addReactDevToolsExtension();
  	createWindow();
  });
  ```
