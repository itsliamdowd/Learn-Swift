# of the Swift Programming Language


## For Loops


## Switches
Switches can be used in Swift to easily control a program depending on the value of something

Switches use the ````switch```` and ````case```` keywords to control which section of the code gets run

An example of a switch to determine the outcome of an election is:
````
var electionResult = "win"

switch electionResult{
    case "win":
        print("win")
    case "loss":
        print("loss")
    case "draw":
        print("draw")
    default:
        print("unknown election result")
}
````

**Project:** Define the variable "didWinElection" and set the value equal to true. Then, write a switch statement that checks if the election was won or lost depending on the value of didWinElection and then print something different to the output

## If Statements
An if statement can help you control the way a program operates depending on if a specific condition or set of conditions are met

An example of an if statement using non programming terms is ````if it's raining now```` then ````close the windows````

In Swift, if statements are used by typing ````if````, ````else if````, and ````else````

An example of an if statement block of code is:
````
var rainyOutside = true

if rainyOutside == true {
    let areWindowsClosed = true
}
else if rainyOutside == false {
    let areWindowsClosed = false
}
else {
    let areWindowsClosed = false
}
````

**Project:** Define the variable "currentWeather" and set the value equal to "rainy". Then, write an if statement that checks if the weather is rainy, sunny, or something else and prints a different output depending on the current weather value

<img width="1430" alt="Current Weather Project" src="https://user-images.githubusercontent.com/101684827/193162513-b617f1fe-48c4-4292-af8c-b998a838321b.png">
