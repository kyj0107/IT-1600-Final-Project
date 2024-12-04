# Binary Multiplication

As with binary addition and subtraction, binary multiplication is a matter of switching between 1 and 0. Below is a neat little chart for remembering how 0 and 1 could possibly interact with each other:

```
0 ✕ 0 = 0
0 ✕ 1 = 0
1 ✕ 0 = 0
1 ✕ 1 = 1
```

Now, let's say you have this equation:

```
  1011
✕   10
------
     ?
```

You would solve this like you would with decimals. Starting from the right, you take that digit of the second operand and it multiply it by the first operand. 1011 ✕ 0 = 0. Then when you move on to the next digit of the second operand, you tack on a 0 at the end. So, 1011 ✕ 1 = 1011, and the extra 0 at the end makes it...

```
   1011
✕    10
-------
      0
+ 10110
-------
  10110
```

... 10110!

Now, for something a little interesting:

```
 11011
✕  101
------
     ?
```

The same rules apply, but since the second operand has 3 digits, as you multiply each digit by the first operand, you add one more 0 to the end. So, you multiply 11011 by 1, then by 0 with an extra 0 tacked on, then by 1 again with another 0 added.

```
    11011
✕     101
---------
  0011011
  0000000
+ 1101100
---------
 10000111
```

After all that, your answer for 11011 ✕ 101 should be 1101100!

And thus, binary multiplication has been learned!

## Where next?

- Homepage
- Binary Division
