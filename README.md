#tech
# Simple String Operations Program
def main():
    # Input a string from the user
    user_string = input("Enter a string: ")

    # 1. Convert to uppercase
    print("Uppercase:", user_string.upper())

    # 2. Convert to lowercase
    print("Lowercase:", user_string.lower())

    # 3. Reverse the string
    print("Reversed:", user_string[::-1])

    # 4. Count number of characters
    print("Length of string:", len(user_string))

    # 5. Check if it is a palindrome
    if user_string == user_string[::-1]:
        print("It's a palindrome!")
    else:
        print("It's not a palindrome.")

main()
