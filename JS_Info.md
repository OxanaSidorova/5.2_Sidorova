# JavaScript operators
### Different types of JavaScript operators:
1. Arithmetic Operators
2. Assignment Operators
3. Comparison Operators
4. Logical Operators
5. Conditional Operators
6. Type Operators

 <details><summary>1. Arithmetic Operators :</summary>
Arithmetic operators are used to perform arithmetic on numbers:

|Operator   |	Description  |
|-----------|   -----------  | 
|+	        |     Addition   |
|-	        |Subtraction|
|*	        |Multiplication|
|**	        |Exponentiation |
|/	        | Division      |
|%	        | Modulus (Division Remainder)|
|++	        |    Increment  |
|--	        |Decrement      |

</details>
<details><summary> 2. Assignment Operators:</summary>
Assignment operators assign values to JavaScript variables.

|Operator|	Example	|Same As|
|--------|----------|-------|
|=|	x = y|	x = y|
|+=	|x += y	|x = x + y|
|-=|	x -= y|	x = x - y|
|*=	x | *= y|	x = x * y|
|/=	x |/= y|	x = x / y|
|%=	x |%= y|	x = x % y|
| **=x | **= y|	x = x ** y|
</details>

<details><summary> 3.Comparison Operators </summary>

|Operator|	Description|
|--------|-------------|
|==      |     equal to|
|===	|equal value and equal type|
|!=	|not equal|
|!==	|not equal value or not equal type|
|>|	greater than|
|<	|less than|
|>=	|greater than or equal to|
|<=	|less than or equal to|
|?	|ternary operator|
</details>
<details> <summary> 4. Logical Operators </summary>

|Operator	| Description|
|----------|-------------|
|&&	|logical and|
||||logical or |
|!	|logical not|
</details>

<details> <summary>5. JavaScript Type Operators</summary>

|Operator	|Description|
|-----------|----------|
|typeof	|Returns the type of a variable|
|instanceof	|Returns true if an object is an instance of an object type|
</details>

<details> <summary> 6.JavaScript Bitwise Operators </summary>
Bit operators work on 32 bits numbers.

Any numeric operand in the operation is converted into a 32 bit number. The result is converted back to a JavaScript number.
|Operator|	Description|	Example	|Same as|	Result	Decimal|
|---|--|----|----|---|
|&	|AND	|5 & 1|	0101 & 0001|	0001	| 1|
| |	OR	|5 || 1	0101 | 0001	0101	 5|
|~|	NOT|	~ 5	| ~0101	|1010	| 10|
|^|	XOR	|5 ^ 1	|0101 ^ 0001	|0100	 |4
|<<|	left shift|	5 |<< 1	0101 << 1	|1010	 10|
| >>	|right shift|	5 >> 1	|0101 >> 1	|0010	 | 2|
|>>>|	unsigned right shift|	5 >>> |1	0101 >>> |1	0010	|  2
</details>
```


# Dynamic type

> JavaScript is called a dynamic language because it doesn't just have a few dynamic aspects, pretty much everything is dynamic. 
> All variables are dynamic (both in type and existance), and even the code is dynamic. You can create new variables at runtime, and the type of variables is determined at runtime.

## Example 
```
let dogName = "Molly"
dogName = true
```
