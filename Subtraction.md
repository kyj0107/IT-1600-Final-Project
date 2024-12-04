# Binary Subtraction

Binary subtraction is kind of weird. It's the same thing as binary addition, where it's a matter of switching around some ones and zeros, but it gets kind of complicated when you have to borrow from other numbers like you would with decimals. You could have equations as simple as this:

```
  110
-  10
-----
  100
```

And then have equations like this:

```
  1011011
-   10010
---------
        ?
```

You can solve this like you would with decimals, but let me introduce you to the Complement Method!

With the Complement Method, you take the second operand and invert it, and then you add 1 to it. Solve it like you would with binary addition, and then add the first operand to that! You should end up with a binary number that has more digits than the largest operand... so get rid of the first digit, and...

```
  1011011
- 0010010 ->   1101101
---------    +       1
             ---------
               1101110
             + 1011011
             ---------
              11001001 -> 1001001
```

... your answer is 1001001!

And there you have it! It's not quite the same process as binary addition, and it might take more steps than necessary, but I find this to be the most straightforward method.

## Where next?

- Homepage
- Binary multiplication
