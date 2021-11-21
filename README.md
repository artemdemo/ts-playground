# TS playground

## Launch scripts

### Run in the terminal

```
npm start src/some-file.ts
```

### Debug run in VS code

There is config file for running current file `.vscode/launch.json`.
Just open `Run and Debug` (see in the sidebar).
In the top menu you'll see "play" button, it will run currently selected file in debug mode (meaning breakpoints will work).

## 3rd party libraries

**@types/node**

Otherwise whenever you use `console.log()`, you'll get an error: "Cannot find name 'console'. Do you need to change your target library?"

**ts-node**

Used to run TS files in node. It will need installed `typescript` along it.

**typescript**

Currently used version of TS
