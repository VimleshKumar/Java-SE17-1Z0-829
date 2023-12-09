# Binary Number Representation

All Java numeric primitives are signed (that is, could represent positive and negative values).

- Java uses a two's complement implementation of a signed magnitude representation of an integer.
- Changing a sign (negative or positive) is done by inverting all the bits and then adding one 
to the result.

Bitwise Complement operator inverts all bits of a number
: The result of the bitwise compliment operator `~a` would be its 'mirrored' binary value: `-(a+1)`

```java
int a = 2;
int b = ~a; // b is -3
```

Compare values to determine the Boolean result:
- Equal to `==`
- Not equal to `!=`
- Greater than `>`
- Greater than or equal to `>=`
- Less than `<`
- Less than or equal to `<=`
- NOT `!` (Boolean inversion)
- AND `&&` bitwise AND `&`
- OR `||` bitwise OR `|`
- Exclusive OR `^`

> `&&` `||` short-circuit evaluation

> `&` `|` `^` full evaluation

Short-Circuit Evaluation
: Short-circuit evaluation enables you to not evaluate the right side of the `AND` and `OR` 
expressions, when the overall result can be predicted from the left-side value.

```text
true    &&  evaluated
false   &&  not evaluated
false   &   evaluated
false   ||  evaluated
true    ||  not evaluated
true    |   evaluated
true    ^   evaluated
false   ^   evaluated
```

> **Note**: It is not advisable to mix Boolean logic and actions in the same expression.
