# python42
Binary combinations
def binary(n,b=''):
    if n==0:
        print(b)
        return(b)
    binary(n-1,b+'0')
    binary(n-1,b+'1')

length=int(input("Enter length of string:"))
print("Binary combinations......")
binary(length)
