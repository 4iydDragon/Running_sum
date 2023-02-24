# Initialize a variable `get_total` to 0.
get_total= 0.0
# While the conidition is True:
while True:
    # Ask the user to enter a number and store it as a float in a variable `inp_numb`.
    inp_numb = float(input("Enter a number (while a negative number to stop): "))
    # If `num` is negative, break out of the loop.
    if inp_numb < 0:
        
        break
    # Print out the final value of `get_total`.
    get_total += inp_numb

print("The final sum is:", get_total)
