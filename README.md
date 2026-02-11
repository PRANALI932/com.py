# com.py
#convert Binary/Octal/Hexadecimal to Decimal

base = int(input("Enter base (2 for Binary, 8 for Octal, 16 for Hex): "))
num = input("Enter the number: ")

print("Decimal equivalent:", int(num, base))

OUTPUT:
Enter base (2 for Binary, 8 for Octal, 16 for Hex): 2
Enter the number: 1011
Decimal equivalent: 11
