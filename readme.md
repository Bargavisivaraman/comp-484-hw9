# JavaScript Built-In Objects

## Built-In Objects and Methods Used

### Date Object:
- `new Date()` - Create a date object for the current date
- `getMonth()` - Get the current month (0-based)
- `getDate()` - Get the current day
- `getFullYear()` - Get the current year

### Number Object:
- `Number()` - Convert values to numbers
- `Number.isNaN()` - Check if a value is NaN
- `Number.isInteger()` - Check if a value is an integer
- `toFixed()` - Format numbers to a specific number of decimal places

### DOM Methods:
- `document.getElementById()` - Select HTML elements
- `.textContent` - Set text content
- `.innerHTML` - Set HTML content

## GitHub Pages Link

https://bargavisivaraman.github.io/comp-484-hw9/

## Screenshot

See `screenshot.png` in this repository.

## Reflection

**What part was easiest?**  
The date formatting was straightforward once I understood that JavaScript months are 0-based and I needed to add 1 to get the correct month number.

**What part was hardest?**  
Creating the conditional logic to check for NaN values and display appropriate messages was challenging at first, but it helped me understand how to validate user input.

**What did you learn about the Date object?**  
I learned that the Date object provides methods to extract individual components like month, day, and year, and that months are 0-indexed (January = 0). I also learned how to format dates by adding leading zeros for single-digit values.

**What did you learn about the Number object?**  
The Number object has powerful validation methods like `isNaN()` and `isInteger()` that help check if values are valid numbers. I also learned that `toFixed()` allows you to format decimal numbers to a specific number of decimal places, which is very useful for displaying grades, prices, and other precise values.

**What did you learn about displaying results in the browser?**  
I learned that you can use `textContent` for plain text and `innerHTML` for HTML content. Using `getElementById()` makes it easy to target specific elements and update them dynamically with JavaScript.

## Course Information

- **Course:** COMP 484
- **Assignment:** Homework 9 - JavaScript Built-In Objects
- **Student:** Bargavi Sivaraman
