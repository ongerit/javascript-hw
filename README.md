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

