# Missing Quotes in getElementById() causing silent failure
This repository demonstrates a subtle bug in HTML/JavaScript where missing quotes around the ID in `getElementById()` leads to a silent failure.  The JavaScript code attempts to hide a div element, but due to the missing quotes, it does not work as intended.

## Bug Description
The bug lies in the JavaScript code that uses `document.getElementById()` to access an element. The ID `myDiv` is passed without quotes.  Browsers will usually fail silently in these scenarios. 

## Solution
The solution involves simply adding quotes around the ID when using `getElementById()`.