

def main():
    print("Welcome to the Addition and Subtraction Program!")
    
    # Get two numbers from the user
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    # Ask the user what operation to perform
    print("Choose the operation:")
    print("1. Addition")
    print("2. Subtraction")
    choice = input("Enter 1 or 2: ")

    # Perform the operation
    if choice == '1':
        result = num1 + num2
        print(f"The result of addition: {num1} + {num2} = {result}")
    elif choice == '2':
        result = num1 - num2
        print(f"The result of subtraction: {num1} - {num2} = {result}")
    else:
        print("Invalid choice. Please enter 1 or 2.")

# Run the program
main()
