# <img src="https://cloud.githubusercontent.com/assets/7833470/10423298/ea833a68-7079-11e5-84f8-0a925ab96893.png" width="60"> Day 1 Assessment

**Instructions:** Do your best! Show your work - we’re more interested in your thought process and problem-solving skills than we are in exact syntax. Feel free to use code or "psuedo-code" (i.e. plain english).

1. Fill in the blank below. When executed, what will the last line of code evaluate to?

	```js
	var student_name = __________;
	var greeting = "Welcome to General Assembly, ";
	console.log(greeting + student_name + "!");
	```
	<br>
	<br>
	<br>
	<br>
	<br>

2. Translate the following webpage into HTML (do not use any CSS styling).

	![simple-html-layout](https://cloud.githubusercontent.com/assets/1489337/13724295/031c7bd2-e836-11e5-882e-c2b24e9c6c9b.png)

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>

3. Given the below code, how would you get the value `30`?

	```js
	var ages = [26, 28, 30, 28, 17];
	```
	<br>
	<br>
	<br>
	<br>
	<br>

4. Given the below code, how would you add the name "Michael Nesmith" to the monkees?

	```js
	var monkees = ["Peter Tork", "Micky Dolenz", "Davy Jones"];
	```
	<br>
	<br>
	<br>
	<br>
	<br>

	**4.1** How would you find the total number of band members?

	<br>
	<br>
	<br>
	<br>
	<br>

5. Given the code below, how would you get the street part of the address?
    ```js
    var address = {
        city: "San Francisco",
        number: 225,
        street: "Bush St.",
        state: "CA",
        zip: 94104
    };
    ```
    <br>
    <br>
    <br>
    <br>
    <br>

6. Given the `combine` function below, what is the output of the following function calls:

	```js
	function combine (a, b) {
		return a + b;
	}

	// input			   //=> output

	combine("1", "2");     //=>
	combine(4, 5); 	       //=>
	combine("8"); 	       //=>
	combine(2, 3, 4); 	   //=>

	var a = 1;
	var b = 7;
	var c = 19 + a;
	combine(c, a);	       //=>
	var x = combine(a, b);
	combine(x, b);	       //=>
	```

7. What is the output of the following code?

	```js
	var rainbowColors = ["red", "orange", "yellow", "green", "blue", "indigo", "violet"];

	for (var i = 0; i <= rainbowColors.length; i++) {
		console.log(rainbowColors[i]);
	}
	```
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>

8. Write a function called `evaluateTemp` that returns "warm" or "cool" depending on the temperature. Anything above 50 degrees is "warm", while anything 50 degrees or below is "cool".

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	
	**8.1** Based on the code you just wrote, what is the output of the following function calls:

	```js
	// input		//=> output

	evaluateTemp(30);  //=>
	evaluateTemp(50);  //=>
	evaluateTemp(70);  //=>
	```

	<img width="706" alt="indicate how confident, how hard" src="https://cloud.githubusercontent.com/assets/1489337/13724610/3d76ecd6-e840-11e5-83b9-4db361a2bd53.png">


9. Write a function called `findGreater` that takes two arguments and returns the greater of the pair.

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>

	**9.1** Based on the code you just wrote, what is the output of the following function calls:

	```js
	// input			      //=> output

	findGreater(7, 0);        //=>
	findGreater(11, 11);      //=>

	var b = 010;
	var s = 100;
	findGreater(b, s) === b;  //=>
	findGreater(s, 1) === s;  //=>
	```

	<img width="706" alt="indicate how confident, how hard" src="https://cloud.githubusercontent.com/assets/1489337/13724610/3d76ecd6-e840-11e5-83b9-4db361a2bd53.png">

10. Name as many JavaScript datatypes as you can think of. **Bonus:** give an example of each!
