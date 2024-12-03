# Binary Addition

Binary addition works no different from "normal" addition: when two numbers in a column add up to a two-digit number, you carry the one over to the next column. Repeat the process a few times, and you have your answer. Where it differs, however, is what adding one to a column of numbers does in binary addition.

Let's use this equation as an example:

```
  1101
+ 1011
------
     ?
```

Since it's nothing but ones and zeros that you can turn on and off, 1 and 0 makes 1, and 1 and 1 makes 0. Basically, if the sum of a column is an odd number, it's 1; if it's an even number, it's 0. And if we apply the rule of carrying the one over to the next column, if 1 and 1 make 0, you carry the 1 over to the next column, so 0 and 1 and 1 would make 0--rinse and repeat as you need, and then--

```
  1101
+ 1011
------
 11000
```

1101 + 1011 is 11000!

And thus, we have completed binary addition!

## Where next?

- Homepage
- Binary Subtraction

