# responsive-calculator
No libraries are used , an experiment with vanilla Javascript. Not necessarily the most optimal solution, but plays with event handler, some media queries using % on widths, Unicodes, and simple HTML.

The Calculator consists of three main sections:
	1) Result
  2) Operators
  3) Number (or 'Operands'). 
	For purpose of simplicity, we just have three pieces of data to hold:
	 first number, operator, second number
	 Decimal and inverse sign are stores as part of the number
	 If there were more operations, a data structure (array) to determine which method to call can be used.
   Another efficient coding strategy can be applied by using stack operations (Infix to Postfix and evaluate). 
	 One can also use specific ID or class for different operations, for instance for addition, I could use '.add' and apply an event.
	 I wanted the calculation to be pretty simple and there's just one function for all the calculations. 

		/ : 47  
		* : 42
		+ : 43
		- : 45 
		% : 37
		= : 61, Enter key is 13
		. : 46
		negation is done by simply adding a '-' twice. That is the only operation allowed twice. 

