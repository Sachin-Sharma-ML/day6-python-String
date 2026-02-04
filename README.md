# day6-python-String
 Python string practice  code

 # -----------------------------
# STRING OPERATIONS IN PYTHON
# -----------------------------

name = "Sachin Sharma"

# String print
print(name)              # Output: Sachin Sharma

# String Slicing
print(name[::])          # Output: Sachin Sharma
print(name[:4:])         # Output: Sach
print(name[2:5:])        # Output: chi
print(name[:12:2])       # Output: Sci hr
print(name[::-1])        # Output: amrahS nihcaS


# -----------------------------
# lower() function
# -----------------------------
name1 = "THIS IS A STR"
print(name1.lower())     # Output: this is a str


# -----------------------------
# upper() function
# -----------------------------
name2 = "this is a str"
print(name2.upper())     # Output: THIS IS A STR


# -----------------------------
# title() function
# -----------------------------
name3 = "this is a str"
print(name3.title())     # Output: This Is A Str


# -----------------------------
# capitalize() function
# -----------------------------
name4 = "this is a str"
print(name4.capitalize())  # Output: This is a str


# -----------------------------
# swapcase() function
# -----------------------------
name5 = "Sachin"
print(name5.swapcase())    # Output: sACHIN


# -----------------------------
# isalpha() function
# -----------------------------
name6 = "hello"
print(name6.isalpha())     # Output: True

name7 = "sachin123"
print(name7.isalpha())     # Output: False


# -----------------------------
# isalnum() function
# -----------------------------
name8 = "hello"
print(name8.isalnum())     # Output: True

name9 = "sachin123"
print(name9.isalnum())     # Output: True


# -----------------------------
# isdigit() function
# -----------------------------
name10 = "hello"
print(name10.isdigit())    # Output: False

name11 = "sachin123"
print(name11.isdigit())    # Output: False

name12 = "123"
print(name12.isdigit())    # Output: True


# -----------------------------
# len() function
# -----------------------------
string = "sachinsharma"
print(len(string))         # Output: 13

