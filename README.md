# Lunar Dates 2018

a piece of javascipt code that returns the Chinese lunar calendar dates for days in 2018 (gregorian calendar).

## Usage

First, include `lunar2018.js`.

Then, call the function `lunar2018(M,D)` in your own scipt. It will return a string of the Chinese lunar calendar date.

## Function Syntax

> lunar2018(M,D)

### Parameters:
* M: a **Number**, indicating the month of the gregorian date (1 to 12 for Jan to Dec). 
* D: a **Number**, indicating the day of the gregorian date (1 to 28/30/31). If only one parameters is given, the default day will be the 1st of that month. If no parameter is given at all, the default date will be Jan 1st.

### Return value:
* The function returns a **string** of the correspondent lunar calendar date in Chinese.
* If one or more invalid value is provided to parameter M or D, the function will return **'Invalid Date'**.

## Example

HTML

```html
<!DOCTYPE html>
<html>
<head>
	<script type="text/javascript" src="lunar2018.js"></script>
</head>
<body>
	...
</body>
</html>

```

Javascript

```javascript
var a=lunar2018(10,10);
document.write(a); // Will output '戊戌年九月初二'.
```