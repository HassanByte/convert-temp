# convert-temp
"Here's the code to convert Kelvin to Celsius and Fahrenheit."
<br>
//this is kelvin 293
const kelvin = 0;
//we are converting the kelvin to celsius
const celsius = kelvin - 273;
//converting celsius to fahrenheit.
let fahrenheit = celsius * (9 / 5) + 32;
//jaanday
fahrenheit = Math.floor(fahrenheit);
console.log(`The tempreture is ${fahrenheit} degrees fahrenheit`);
