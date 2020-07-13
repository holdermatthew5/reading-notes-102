- code works like an instruction manual. The browser reads the full code then starts performing the steps in the order they are read using definitions assigned anywhere in the code. in an attempt at remaining user friendly these definitions should be made where they will first be used if possible. steps can be skipped if they are not needed right away and they can be used again by later steps if needed.
- expressions generally assign value. they can be assigned a set value or they can use multiple values to assign a single value like say that 3 = 3 or saying that 3 = 1 + 2.
- operators are what determines what will be assigned as the meaning. + indicates that 2 or more values will be added together and the result will be assigned as the value, - indicates that 2 or more values will be subtracted from eachother and the result will be assigned as the value. These are known as arithmetic operators and also include * and / as multiplication and division respectively. single quotes (' ') are called assignment aoperators and indicate that whatever is held inside will be the total value assigned `var one = '1+2'` assigns the variable "one" a value of 1+2 instead of 3. the greater than (>) less than (<) symbols (or comparison operators) will assign a true or false value depending on wether the first value is a larger number than the second. a string operator (+) combines two strings `'str' + 'ing'` assigns the value 'string'. a logical operator combines 2 or more comparison operators to also assign a value of true or false.
- `++` - add 1 and assign as new value
- `--` - subtract 1 and assign as new value
- `%` - returns the remainder of division (3 % 2 will return 1)
- a function creates an action to be performed. this can range in complexity from finding the area of a square to creating a new website at the users push of a button and more. they are formatted as follows:
```
function functionName() {
    document.write('Hello!');
}
```
this function simply types "Hello!" on screen. functionName can be changed to anything you desire but to make it easier on future programmers should relate to the intended action of the function. If the function requires information to complete the action it should be placed in the parenthesis as shown:

```
function getArea(width, height) {
    var width = 3
    var height = 5
}
```

width and height are defined in the fuction as strict numerical values here but can be designed to be input by the user.