# Password Generator Program (Student Level)

import random
import string

print("--- PASSWORD GENERATOR ---")

# User input for password length
length = int(input("Enter the desired password length: "))

# Characters to choose from
characters = string.ascii_letters + string.digits + string.punctuation

# Generate password
password = "".join(random.choice(characters) for _ in range(length))

# Display password
print(f"Generated Password: {password}")
