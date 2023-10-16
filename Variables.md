# Variables
To store the date in our programs, we use variables. Variables have a name, a type and a value.
## Declaration
A variable declaration in Shard looks like this:
```
var name: type = value;
```
The declaration starts with the keyword "var", followed by the name, type and finally the value.
```js
var health: int = 100;
```
## Getting the value
As mentioned earlier, variables store the data of the program. We can get a data from a variable using the name of that variable.
```js
var amount: int = 10;
var amountSquared: int = amount * amount;

Console.write(amount); // output: 10
Console.write(amountSquared); // output: 100
```
## Setting the value
In addition to getting the value from a variable, we can also set it in the program.
```js
var health: int = 100;
Console.write(health); // output: 100
health = 50;
Console.write(health); // output: 50