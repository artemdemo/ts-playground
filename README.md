# TS playground

Typescript playground repo. Minimum setup to run TS files on node.

## Launch scripts

### Run in the terminal

```markdown
npm start src/test.ts
```

### Debug run in VS code

There is a config file to run TS files `.vscode/launch.json` via debug mode of VS code. Just open `Run and Debug` (see in the sidebar on the left). In the top-left corner of the IDE window, you'll see the "play" button; it will run the currently selected file in debug mode (meaning breakpoints will work).

## 3rd party libraries

- **@types/node**

  Otherwise, whenever you use `console.log()`, you'll get an error: "Cannot find name 'console'. Do you need to change your target library?"

- **ts-node**

  Used to run TS files in node. It will need `typescript` installed alongside.

- **typescript**

  Currently used version of TS
