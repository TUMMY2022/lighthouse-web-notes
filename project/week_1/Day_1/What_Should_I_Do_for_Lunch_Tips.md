### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
```Javascripting
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("Go back to work.");
  } else {
    if (availableTime < 20) {
      console.log("pick something up and eat it in the lab");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("Let me try a resturant close to me");
    } else if (availableTime > 30) {
      console.log("we're in a bootcamp, so I should reconsider how much time I actually have to spare.");
    }
  }
};
```