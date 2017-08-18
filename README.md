# responsive-calculator
No libraries are used , an experiment with vanilla Javascript. 
Use to play with event handlers, apply media queries (RWD), Unicodes.
Simple HTML is used, code can be optimized using different algorithms. 

        The Calculator consists of three main sections:
        1) Result
        2) Operators
        3) Numbers (or 'Operands'). 
	Let's assume 3 pieces of data are held: first number, operator, second number
        
                / : 47  
		* : 42
		+ : 43
		- : 45 
		% : 37
		= : 61, Enter key is 13
		. : 46
		negation is done by simply adding a '-' twice. That is the only operation that's allowed to be input twice. 

	Other assumptions:
	Decimal and inverse sign are stores as part of the number
	If there were more operations, a data structure (array) to determine which method to call can be used.
	Another efficient coding strategy can be applied by using stack operations (Infix to Postfix and evaluate). 
	One can also use specific ID or class for different operations, for instance for addition, I could use '.add' and apply an event.
