# Binary Subtraction

Binary subtraction is kind of weird. It's the same thing as binary addition, where it's a matter of switching around some ones and zeros, but it gets kind of complicated when you have to borrow from other numbers like you would with decimals. So, let me show you the Complement Method!

```
  101
-  11
-----
    ?
```

With the Complement Method, you take the second operand and invert it, and then you add 1 to it. Solve it like you would with binary addition, and then add the first operand to that! You should end up with a binary number that has more digits than the largest operand... so get rid of the first digit, and...

```
  101
- 011 ->   100
-----    +   1
         -----
           101
         + 101
         -----
          ~~1~~010
```

