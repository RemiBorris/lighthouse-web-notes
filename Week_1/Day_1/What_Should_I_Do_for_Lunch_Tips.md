### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in your terminal.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
// begin by checking if your are hungry or not
  if (hungry === false) {
    console.log("Wait till you're hungry");
    // if your are hungry, how much time do you have?
  } else if (availableTime < 20) {
    console.log("Pick up a snack or eat something ready from home");
  } else if (availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break, go cook a tasty meal");
  } else console.log("This is an intense program, you should reconsider");
};
```