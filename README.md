# python-insert-list-element

# Python program to insert a number at any position in a list

numbers = [3, 4, 1, 9, 6, 2, 8]
print("Original list:", numbers)

# Input number and position
x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position (index) to insert the number: "))

# Check if position is valid
if 0 <= y <= len(numbers):
    numbers.insert(y, x)
    print("Updated list:", numbers)
else:
    print("Invalid position! Please enter a number between 0 and", len(numbers))


OUTPUT:

Original list: [3, 4, 1, 9, 6, 2, 8]
Enter the number to be inserted: 7
Enter the position (index) to insert the number: 3
Updated list: [3, 4, 1, 7, 9, 6, 2, 8]
