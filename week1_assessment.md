# Week 1 Assessment

### Bash (Terminal)

#### Assume your present working directory is `$ ~/buffy`

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`
<br><br><br>
mkdir scoobies
mkdir vamps

2. Make files in `scoobies` named `buffy.txt`, `giles.txt` and `angel.txt`
<br><br><br>

touch scoobies/buffy.txt
touch scoobies/giles.txt
touch scoobies/angel.txt

3. Copy `angel.txt` into the `vamps` directory
<br><br>

cp scroobies/angel.txt vamps/angel.txt

4. Delete the `vamps` directory and everything inside it
<br><br>

rm -r vamps
### JS Variables

1. Assign the string "Jack" to a variable called `captain`
<br><br>
var capitan = "Jack";

2. Using the `captain` variable, use string concatenation to form the string "Oh Jack, my Jack!", assigning it to a variable named `phrase`
<br><br>

var phrase = "Oh "+capitan+", my "+capitan; 


### JS Conditionals
```js
var souls = 3;
var lifeRafts = 2;
```

1. Write an `if` statement that console.logs "SOS!" if there are more _souls_ than _lifeRafts_
<br><br>


### Data Structures - JS Arrays

1. Create an array named `weekend` with just 'Saturday' in it
<br><br>
var weekend = ["Saturday"];
2. Add 'Sunday' to the end of the `weekend` array
<br><br>
weekend.push("Sunday");
3. Add 'Friday' to the front to the front of the `weekend` array
<br><br>
weekend.unshift("Friday");

4. Access 'Saturday' in the array and assign to a variable named `day`
<br><br>
var day = weekend[1];

5. Remove 'Friday' from the array
<br><br>

weekend.shift();
### Data Structures - JS Objects

1. Write an object literal named `brain` having a property of `energyLevel` with a value of `10`
<br><br>
var brain = {energyLevel:4}
    
2. Assign the property of `energyLevel` to a variable named `energy`
<br><br>
energy.
brain.energyLevel;

3. Add a `dream` property to the `brain` object that holds the string  'electric sheep'
<br><br>
brain.dream = "electric sheep";
### JS Functions

1. Write a function to return the area of a rectangle (the product of its length and its width)
<br><br>
var area= function(num1,num2){
    return num1* num2
}
2. Invoke the function with `3` and `4` as arguments and save it to a variable
<br><br>

var outcome = area(3,4);

