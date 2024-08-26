let num = Number(prompt("Enter your exam score:"));

if (num > 100) {
    console.log("Invalid Score");
} else if (num < 0) {
    console.log("Invalid Score");
} else if (num === 100) {
    console.log("Perfect Score");
} else if (num >= 85) {
    console.log("You got an A");
} else if (num >= 75) {
    console.log("You got a B");
} else if (num >= 65) {
    console.log("You got a C");
} else if (num >= 50) {
    console.log("You got a D");
} else if (num >= 0) {
    console.log("You got an F");
} else {
    console.log("Not a Number");
}
