### Tips
Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
### Code

```function whatToDoForLunch (hungry, availableTime) {
  const hungry = true;
  const availableTime = 17;
  if (hungry === true && availableTime < 20) {
    console.log("Go grab a quick snack")
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log("Take a break and cook something tasty")
  } else {
    console.log("You're in bootcamp and should reconsider how much time you have to spare")
  }
} ```