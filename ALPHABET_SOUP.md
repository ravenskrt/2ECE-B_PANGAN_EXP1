#Define a function
def alphabet():
    #Prompt the user to enter a string and store in variable x
    x=input("Enter string: ")
    #Sort the entered string by converting it into a list of characters
    sorted_chars=sorted(x)
    #Use slicing to unite the sorted characters in one string
    sorted_string=''.join(sorted_chars[:])
    #Print the sorted string
    print(sorted_string)
#Call the alphabet function to execute
alphabet()
