# calculation
Normal_Calculation

console.log ("Problem solving")


// Basic of calculation 
let a = 10;
let b = 5;

console.log(a + b); // Addition: 15
console.log(a - b); // Subtraction: 5
console.log(a * b); // Multiplication: 50
console.log(a / b); // Division: 2
console.log(a % b); // Modulus (remainder): 0
console.log(a ** b); // Exponentiation (10^5): 100000





// increment & dicrement

let x = 5;
x++;  // Increases by 1
console.log(x); // 6

x--;  // Decreases by 1
console.log(x); // 5


// ************************************
let name = "Shuvo"; // String
const age = 25; // Number
var isDeveloper = true; // Boolean

console.log(name, age, isDeveloper);






/***************Score*******************/

let score = 85;

if (score >= 90) {
    console.log("Grade: A");
} else if (score >= 80) {
    console.log("Grade: B");
} else {
    console.log("Grade: C");
}

// Using Switch
let day = "Monday";
switch (day) {
    case "Monday":
        console.log("Start of the week!");
        break;
    case "Friday":
        console.log("Weekend is near!");
        break;
    default:
        console.log("A normal day.");
}


//**********For & wile loops*************//
// For Loop
for (let i = 1; i <= 5; i++) {
    console.log("Number:", i);
}

// While Loop
let j = 1;
while (j <= 5) {
    console.log("While Loop:", j);
    j++;
}



********************************************************
Decrease a number by a percentage
js
Copy
Edit
let number = 100;
let decreasePercent = 15;

let result = number - (number * decreasePercent / 100);
console.log(result); // 85


*********************************************************
🔥 3. Body Mass Index (BMI) Calculator
js
Copy
Edit
function calculateBMI(weightKg, heightCm) {
  let heightM = heightCm / 100;
  return (weightKg / (heightM ** 2)).toFixed(2);
}


********************************************************
Scroll Progress Indicator
Dynamic scroll % calculation for any page:

js
Copy
Edit
window.addEventListener('scroll', () => {
  const scrollTop = window.scrollY;
  const docHeight = document.documentElement.scrollHeight - window.innerHeight;
  const scrollPercent = (scrollTop / docHeight) * 100;
  console.log(`Scroll: ${scrollPercent.toFixed(2)}%`);
});


/***************Score*******************/

let score = 85;

if (score >= 90) {
    console.log("Grade: A");
} else if (score >= 80) {
    console.log("Grade: B");
} else {
    console.log("Grade: C");
}

// Using Switch
let day = "Monday";
switch (day) {
    case "Monday":
        console.log("Start of the week!");
        break;
    case "Friday":
        console.log("Weekend is near!");
        break;
    default:
        console.log("A normal day.");
}








🔥 3. Body Mass Index (BMI) Calculator js Copy Edit function calculateBMI(weightKg, heightCm) { let heightM = heightCm / 100; return (weightKg / (heightM ** 2)).toFixed(2); }

Scroll Progress Indicator Dynamic scroll % calculation for any page:

js Copy Edit window.addEventListener('scroll', () => { const scrollTop = window.scrollY; const docHeight = document.documentElement.scrollHeight - window.innerHeight; const scrollPercent = (scrollTop / docHeight) * 100; console.log(Scroll: ${scrollPercent.toFixed(2)}%); });

/Score****/

let score = 85;

if (score >= 90) { console.log("Grade: A"); } else if (score >= 80) { console.log("Grade: B"); } else { console.log("Grade: C"); }

// Using Switch let day = "Monday"; switch (day) { case "Monday": console.log("Start of the week!"); break; case "Friday": console.log("Weekend is near!"); break; default: console.log("A normal day."); }


