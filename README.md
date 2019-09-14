import random
picked_number = 1
print("picked_number = " + str(picked_number))
x =int(input("enter your guess: "))
guessed_number = 1
#print ("The random number is: " + str(picked number) + " and the guessed number is " + str(x)

while (picked_number != x):
    if(x < picked_number):
        print("increase the value of your guess")
    if(x > picked_number):
        print("increase the value of your guess")
    x = int(input("enter your new guess: "))
    guessed_number += 1
print("successfull!! number of guesses is: " + str(guessed_numbers))
