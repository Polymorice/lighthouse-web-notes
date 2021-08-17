### Tips

instruction tips:

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```

---

Personal tips:

Notice that `hungry` is the primary parameter, the the `availableTime` conditon should be nested in the primary condition.

`switch` is not applicable, since we are dealing with intervals here.
