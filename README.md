# TS playground

Typescript playground repo. Minimum setup to run TS files on node.

## Launch scripts

### Run in the terminal

```
npm start src/test.ts
```

### Debug run in VS code

There is config file to run ts files `.vscode/launch.json` via debug mode of VS code.
Just open `Run and Debug` (see in the sidebar).
In the top-left corner of the IDE window you'll see "play" button, it will run currently selected file in debug mode (meaning breakpoints will work).

## 3rd party libraries

**@types/node**

Otherwise whenever you use `console.log()`, you'll get an error: "Cannot find name 'console'. Do you need to change your target library?"

**ts-node**

Used to run TS files in node. It will need installed `typescript` along it.

**typescript**

Currently used version of TS
