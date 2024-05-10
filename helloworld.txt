str="Hello World"
for x in str:
    print (x)
    print("Position of each string in each character", str.index(x))
    xoroper = 127 ^ str.index(x)
    print("Printing the XOR operator results:", xoroper)
    andoper = 127 & str.index(x)
    print("Printing the AND operator results:", andoper)
    oroper = 127 | str.index(x)
    print("Printing the OR operator results:", oroper)
