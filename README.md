# HomeWork-2  
## Quick Overview
Most instances in JavaScript are considered objects excepts for Primitive data (Strings, Numbers and Booleans) and Composite (Array) data. 

**Primitives**  
Primitive data are single discrete data points.  
**Const** is used when we want the data entered in to be non-mutable, were as with **Let** is used to make the data mutable / changeable.  
const A = ‘Hello, Nice to meet you!’;

const B = 21;

let C = 3;

**Composite**  
Composite data are a single entity that hold multiple entities that are related to each other. Such as Arrarys and lists.

**Array**  
const person = [{name: "Dee", age: 24, status: "Student"}, {name: "Mike", age: 31, status: "Working"}];

person[0].status == Student

person[1] == { name: “Mike”, age: 31, status: “Working”}

person[2] gives nothing. Remember that arrays count objects starting from 0 and up. {name: "Dee", age: 24, status: "Student"}   
equals 0, and 2 stands for {name: "Mike", age: 31, status: "Working"}.

**Template Literals**  
Template literals are used to substitute variables into strings. This is used to combine variables such as numbers or strings. 

let a = 15;

let b = 9;

const c = “My car is less than “ + (a + b) + “ years old.”

This would display:  **My car is less than 24 years old.**

**If-Else & Ternaries**  
If-else are conditional statement that choses either to do one thing  or another based on the expression is true or false.  
Basically, a true or false question with a coded outcome. 

const a = [name: “Sid”,  age: 24]

const b = [name: “Blake”,  age: 17]

if (variable.age >= 18) {“Yes, “ + (variable.name) + “ can buy cigarettes to smoke.”  
} else {“No, “ + (variable.name) + “ is not old enough to buy cigarettes to smoke.”}

const a = Yes, Sig can buy cigarettes to smoke.  
const b = No, Blake is not old enough to buy cigarettes to smoke  
In the case of  a, Sid can buy cigarettes; but with b, Blake would not be.

Ternaries are If-Else statements with a briefer way of being written. Like (Q ? “outcome a” :” outcome b”)

**Switch-case**  
Switch-cases are used to compare the values of a selected variable to the values within the statement.  
Mainly used when you want to create predetermine answers for predetermine questions, or for making Switch  
Boards which are used as display menus on simple robot calls or applications.

Const student = [name: “Maverick”, status: “re-enrolling”]

Switch (student.status) {  
Case “enrolling” :  
	
	Enrollment;  
	Degree(student);  	
	Class;  	
	Tuition;  
	Console.log(“Welcome and hope you enjoy your school yea.r”)  
	Break;

Case “re-enrolled”:  
	
	Degree(student):  
	Class;  	
	Tuition;  
	Graduation;  
	Console.log(“Happy to have you back for another year.”)  
	Break;

Default: 

	Console.error(“This student is not enrolled in our school.”;

}

For this example, the outcome of the switch-case would be case “re-enrolling. It will trigger, and all code  
associated with said case.

**Remember** switch-cases are case sensitive, as in even if they are spelled the same but have one letter  
capitalized, then the default case will be the only one to trigger. 

**Logical Operators**  
These are operators that can be used with Switch-case, If-else statements and Ternaries to enhance the   
true and false parameters of A statement. These operators are **And (&&)** and **Or (||)**  
And is added when you want to make sure the outcome or stamen includes both variable a and b.  
Example:  
 Const a = 3  
Const b = 9
Const c = 10
If (a=== “3” && c === “15”) {console .log(“Variable A + B equals 18.”)  
} else{ console .log(“Variable A + B dose not equal 18.”)}

Here we used the AND parameter to compare both a and b. If neither instance is correct  
then the else is triggered. While if we used the OR parameter, then only one of the   
compared variables need match for the true value to occur. 

cosnt answer = c

If (answer === a || answer ===c) {console .log(“Correct!”)  
} else{ console .log(“Incorrect, answer was either A or C.”)}

**Mutations**  
Mutations are changes that occur to the original data variable and not the called instances.  
Example: Let’s say you have an array full of names.

const names = [ “Amy”, “Carl”, “Sam”, “Phill”]

if you wanted to add a temporary name to the list, then you would use variable.push(new name) to add them.

names.push(“Kim”)

Now when names are called, it will display**Amy, Carl, Sam, Phill, Kim**; overwriting the original variable.  
But if you want to keep the original variable but create a single instance copy of the variable with changes made to it,  
then you would need to use a Spread operator. To do so, first assign a new variable then set it equals to variable, then the change  
or changes you want to occur, with  (…) added to the beginning of the variable.  

Const newNames = (…names, “Kim”)

Now, with the spread operator added, if we call on names then we will get:  **Amy, Carl, Sam, Phill**.  
While if we call newNames we will get: **Amy, Carl, Sam, Phill, Kim**.  
