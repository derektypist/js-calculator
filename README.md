# JavaScript Calculator

Welcome to JavaScript Calculator.  The purpose of this project is to have functionality similar to
https://codepen.io/freeCodeCamp/full/wgGVVX

## UX

The calculator has plus, minus, multiply, divide and percent buttons.  It also has a change of sign from plus to minus and vice versa.

### User Stories

User stories taken from https://www.freecodecamp.org/learn/front-end-libraries/front-end-libraries-projects/build-a-javascript-calculator

My calculator should contain a clickable element containing an = (equal sign) with a corresponding id="equals".

My calculator should contain 10 clickable elements containing one number each from 0-9, with the following
corresponding IDs: id="zero", id="one", id="two", id="three", id="four", id="five", id="six", id="seven", id="eight", and id="nine".

My calculator should contain 4 clickable elements each containing one of the 4 primary
mathematical operators with the following corresponding IDs: id="add", id="subtract", id="multiply", id="divide".

My calculator should contain a clickable element containing a . (decimal point) symbol with a corresponding id="decimal".

My calculator should contain a clickable element with an id="clear".

My calculator should contain an element to display values with a corresponding id="display".

At any time, pressing the clear button clears the input and output values,
and returns the calculator to its initialized state; 0 should be shown in the element with the id of display.

As I input numbers, I should be able to see my input in the element with the id of display.

In any order, I should be able to add, subtract, 
multiply and divide a chain of numbers of any length, and when I hit =, the correct result should be shown in the element with the id of display.

When inputting numbers, my calculator should not allow a number to begin with multiple zeros.

When the decimal element is clicked, a . should append to the currently displayed value; two . in one number should not be accepted.

I should be able to perform any operation (+, -, *, /) on numbers containing decimal points.

If 2 or more operators are entered consecutively, the operation performed should be the last operator entered (excluding the negative (-) sign).
For example, if 5 + * 7 = is entered, the result should be 35 (i.e. 5 * 7); if 5 * - 5 = is entered, the result should be -25 (i.e. 5 x (-5)).

Pressing an operator immediately following = should start a new calculation that operates on the result of the previous evaluation.

My calculator should have several decimal places of precision when it comes to rounding (note that there is no exact standard,
but you should be able to handle calculations like 2 / 7 with reasonable precision to at least 4 decimal places).

Note On Calculator Logic: It should be noted that there are two main schools of thought on calculator input logic: immediate execution logic and formula logic. Our example utilizes formula logic and observes order of operation precedence, immediate execution does not. Either is acceptable, but please note that depending on which you choose, your calculator may yield different results than ours for certain equations (see below example). As long as your math can be verified by another production calculator, please do not consider this a bug.
EXAMPLE: 3 + 5 x 6 - 2 / 4 =
Immediate Execution Logic: 11.5
Formula/Expression Logic: 32.5

[Wireframes](wireframes/wireframe-js-calculator.png) are supplied.

## Features

This calculator has 19 buttons.  10 number keys, 6 operations (add, subtract, multiply, divide, percent
and change sign - positive to negative and negative to positive), equals key, decimal key and clear key.


## Technologies

This project uses HTML5, CSS3, Bootstrap 4.4.1, jQuery 3.4.1 and Bignumbers (available at https://www.jsdelivr.com/package/npm/mathjs).

## Credits

### Content

Written by me.

### Acknowledgements

[Kristin Anthony](https://www.knanthony.com/blog/free-code-camp-calculator) - including the [code pen](https://codepen.io/anthkris/pen/vLdgev).
Accessed on 18 February 2020.

The [MathJS Library](https://mathjs.org/index.html), accessed on 20 Feburary 2020.







