# Read: 08 - Operators and Loops

JavaScript Expressions and operators. an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate. JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator: An assignment operator assigns a value to its left operand based on the value of its right operand.

JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, and ternary.

1. An expression is a valid code that can result in a value.

2. There are two types of expressions: those that have side effects and those that don't

an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer's mistake because the evaluation doesn't produce any effects.

all complex expressions are joined by operators, such as = and +

Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
BigInt operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators

1. The operators that join operands are those that are higher up in the precedence tree.

2. These operators join operands by putting them together, just like the basic expressions.

*The precedence of operators determines the order they are applied when evaluating an expression. For example:*

const x = 1 + 2 * 3;
const y = 2 * 3 + 1;

Despite * and + coming in different orders, both expressions would result in 7 because * has precedence over +, so the *-joined expression will always be evaluated first. You can override operator precedence by using parentheses (which create a grouped expression — the basic expression). To see a complete table of operator precedence as well as various caveats, see the Operator Precedence Reference page.

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:


*3 + 4 or x * y. This form is called an infix binary operator*

## What I'd like to learn more about. 

Learn more useful assignment operators 
How to better assign properties 
what is Destructuring
What are evaluation and nesting 

[*Source:*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)