# Binary Division

Just like with binary multiplication, binary division can use the same rules when you're solving for decimals!

To start:

```
111 / 11 = ?
```

What you want to do here is long division--fit the divisor into the dividend as early as you can, and then go from there. In this case, 11 fits into the first two digits of 111, so you have a 1 in the tens place so far. However, it won't fit into the leftover 1, so...

```
      10
11 / 111
   - 11|
   ----v
      01
```

You end up with 10 with a remainder of 1.

As for equations like this:

```
1011 / 11 = ?
```

As you go through long division, you'd have to borrow. You can still use the Complement Method from before, though! Again, it adds some extra steps to the process, but I still find it to be the most straightforward way of going about it.

```
       11
11 / 1011 ---------------¬
   - 011 ->   100        |
   -----    +   1        |
            -----        |
              101        |
            + 101        |
            -----        v
             1010 ->   101
                     - 011 ->   100
                     -----    +   1
                              -----
                                101
                              + 101
                              -----
                               1010 -> 10
```

And so, 1011 / 11 = 11 with a remainder of 10!

## Congrats! You've learned binary arithmetic!

- [Homepage](https://github.com/kyj0107/IT-1600-Final-Project/blob/main/README.md)
