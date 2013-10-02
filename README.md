##Homework for NYU Javascript class
---
###Notes for 10-03
####Arrays
1. Unlike php Arrays in Javascript are elastic
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

