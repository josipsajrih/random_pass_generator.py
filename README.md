# random_pass_generator.py
Radom pass generator

import random
chars = "abcdefghijklmnopqrstuvwxyz1234567890#@"
password = ""
number = input("Koliko znakova ti treba:")
int1 = int(number)
for i in range(int1):
    password += random.choice(chars)
print(password)
