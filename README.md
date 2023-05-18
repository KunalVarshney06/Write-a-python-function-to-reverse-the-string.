# Write-a-python-function-to-reverse-the-string.
def
   reverse_string(str): 
   str1 = ""
   for i in str:
      str1 = i + str1
   return str1 # return the reverse string
str = "SimplyCoding" # input String 
print("The original string is: ",str)
print("The reverse string is",reverse_string(str)) # Function call
