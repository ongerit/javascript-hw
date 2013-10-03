##Homework for NYU Javascript class
---
###Notes for 10-02
####Arrays
1. Unlike php Arrays in Javascript is elastic
2. To remove elements from an array we use splice
3. splice (element_index,number_of_elents_to_remove)
	var array1 = [“Sam”, “John”, “Bill”, “David”, “Jim”];
		var stuff    = [“Sam”, “John”, “Bill”, “David”, “Jim”, [1,2,3,4], “jack”];

		array1.splice(2, 1);						//removes “Bill”
		document.write(array1); 					//Sam,John,David,Jim

		stuff[5].splice(1, 2);						//removes 2 and 3 
		stuff.splice(5, 1);						//removes entire inner array


####Objects within objects
1. [Object Name] [PropertyName] 
2. ['family'] ['mother'] ['sex']

###Notes for PART 2 : Logic and Program Control

####Sequential processing

####Conditional Processing -- if(...)

1. The if() Statement

	if  (comparison expression)
statement to execute if true;

2. JavaScript does not have "elseif" you have to write "else if"

3. Single equal sign we know to look at the right-hand side 

4. The switch() Statement

			var nope = ‘no’;	
		var response = prompt(“Please enter your response, Yes or No”, “”);
		switch (response) {
			case ‘Yes’:								//if equal to ‘Yes’
			case ‘yes’:								//or equal to ‘yes’
				document.write(“Thank you for your order”);
				break;
			case ‘No’:
			case  nope:								//using a variable
				document.write(“You have chosen to cancel the order ”);
				break;
			default:
				document.write(“Invalid option, please choose Yes or No”);
		}

*Allows you to have multiple conditions
*Has to be exact (case-sensitive)
*Key words _switch,case,break_
*If you don't exit with break....It will print all items after... 
*A break will make it exit _Very Important_





####Iterative Processing-- while (...)

	var i=1;

	while (i<=6)
		{
	document.write("<h"+i+">Hello World<h"+i+"><br>");
	i++;
	}
*For loop works exactly like the while loop but the syntax is different

	for  (count = 1;  count <= 100;  count++) 
	{
	document.write(“Loop number: ” + count + “ <br>”);

	}
	document.writeln(“Done counting!!!”);

*For loop (Nested Loop)
Example1:	A simple nested loop:

	for (row = 1; row <= 12; row++)				//loop 12 times
			{
				for (col = 1; col <= 30; col++)			//loop 30 times
				{
					document.write(col + ",");			//print the col number
				}
				document.write("<br> ");				//next line
			}

Example2:	Replacing a ‘for’ loop for a ‘while’ loop:
			for (row = 1; row <= 12; row++)				//loop 12 times
				{
					var col = 1;
					while( col <= 30)					//loop 30 times
					{
						document.write(col + ",");			//print the col number
						col++;						//add 1 to col number
					}
					document.write("<br> ");				//next line
				}

# Above text will help with the homework #
========

###Functions

A function is a block of code that is designed to perform a specific task.   It is up to you to design and develop the code that is inside the function.   To declare a function, use the following syntax:

	>function  functionName  ( parameter1, parameter2, ….)
		{
			JavaScript code to handle a particular task
		}

1. Functions do not get called automatically. They have to be called.

###Global Variabl
1. To localize a variable to you have to use var. If you do not use var, the variable is globalized. 
