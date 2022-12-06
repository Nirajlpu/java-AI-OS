# java-AI-OS

import random
import string
print("Hello usser , Welcome To password Generator!")
# input the length of password
length =int(input("Enter the length of password:"))
# define the data
lower =string.ascii_lowercase
upper =string.ascii_uppercase
num =string.digits
symbols =string.punctuation
# combine the data in single variable
all =lower + upper + num + symbols
# use random
temp = random.sample(all,length)
# create the password
pwd ="".join(temp)
# print random password
print(pwd)
