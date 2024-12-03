# Binary Multiplication

Before we get into binary multiplication, let's have a look at how you can multiply two integers by hand. Let's say you have this equation:

```
  48
✕ 52
----
   ?
```

The first step would be to take the ones digit of the second operand and multiply it by the first operand. In this case, 48 ✕ 2 = 96.

The second step is basically the same thing, but with the tens digit and a 0 tacked on at the end (as you go through the digits of the second operand, you add one more 0 at the end of the solution). So, 48 ✕ 5 is 240, and the additional 0 at the end makes it 2400.

The third step would be taking those two solutions and adding them together! So...

```
    48
✕   52
------
    96
+ 2400
------
  2496
```

... the answer is 2496!

As for binary multiplication, you can sort of apply the same rules you would with decimals on 0 and 1. That is:

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

Starting from the right, you take that digit of the second operand and it multiply it by the first operand. 1011 ✕ 0 = 0. Then when you move on to the next digit of the second operand, you tack on a 0 at the end. So, 1011 ✕ 1 = 1011, and the extra 0 at the end makes it...

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
