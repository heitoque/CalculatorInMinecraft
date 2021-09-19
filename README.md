# CauculatorInMinecraft
A calculador made by redstone that multiplies 1 digit integers.

version: 1.12.2

Part 4 not done yet

How it works(need to know: how to do binary multiplication and how redstone works):

1-converts a redstone line that represents a number into binary

2-compares the bits of both numbers with an and gate

3-adds the equaly valuable bits with an xor and and gate combined

4-converts back the binary numbers into decimal numbers by checking the variation of value of the numbers

--for example:

--11 = 1011

--12 = 1100

--there are variations on the 1 2 and 3 bits so we need to invert those values

-observations

1-the cauculator has its gates ready for 15x15 (max) but the entrys and exits arent

2-the eigth bit is unreacheable in a 4bits*4bits layout, but it makes sence transistorwise
