No libraries are used, wanted to experiment with vanilla JavaScript.
Not necessarily the most optimal solution, but shows how to use event handler,Unicodes and simple HTML.
The Calculator will have three main sections:
	The result, the operators, and the numbers. 
	For purpose of simplicity, we just have three pieces of data to hold:
	 first number, operator, second number
	 Decimal and inverse sign are stores as part of the number
	 If there were more operations we could use a data structure (array) to determine which method to call
	 We could also use specific ID or class for different operations, for instance for addition, I could use '.add' and apply an event.
	 I wanted the calculation to be pretty simple and there's just one function for all the calculations. 

		/ : 47  
		* : 42
		+ : 43
		- : 45 
		% : 37
		= : 61, Enter key is 13
		. : 46
		negation is done by simply adding a '-' twice. That is the only operation allowed twice. 
