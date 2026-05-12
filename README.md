# python_begininglevel.
If you need more practice, follow along. Books I'm using are Python Crash Course and Automate the Boring Stuff with Python.

PCC = Python Crash Course 3rd edition

ATBS = Automate the Boring Stuff with Python and workbook

Read chapters 1 & 2 in PCC and chapter 1 in ATBS.
# practice variables

message = Hello World!

print(message)

change the variable to: house, car, food, animal, place, etc...

change the value to: Hello Friend, I love food, We want to learn,  etc... be creative 

You officially understand from PCC chapter 1-2

print()

variables

strings

numbers

f-strings

comments

simple math

input/output thinking 

debugging small errors

# Exercise 1

Favorite Food List

foods = ["tacos", "pizza", "sushi"]

print(food[0])

print(food[1])

print(food[2])

Add 2 more foods
print a sentence using f-strigs

solution:

food = ["tacos", "pizza", "sushi"]

print(food[0])

print(food[1])

print(food[2])

food.append("apple")

print(food)

print(f"My favorite food is {food[0]}")

# Exercise 2

Mood Tracker

mood = ["happy", "tired", "bored"]

Created a question: "What mood number do you want to see?" (make your own)

print the mood

solution:

mood=["happy", "tired", "bored"]

mood=input("how are you feeling today?").lower()

if mood == "happy":

  print("good for you")

elif mood == "tired":

  print("go to sleep")

elif mood == "bored":

  print("dance")

else:

  print("invalid mood")

# Exercise 3

Score List

score = [10, 25, -5, 50]

print all scores

print the highest score

Add a new score

-----this is new, and you would really enjoy this new trick 

----score.append(100)

----Now you can add 1 extra item to our lists.

solution:

score = [10, 25, -5, 50]

print(score)

print(f"highest score:{score[3]}")

score.append(75)

print(score)

# Exercise 4

Shopping List Mini App

make a shopping list using: shopping [  ]

print shopping list

add extres item(s) using .append (  )

print shopping list 

and repeat, see how the list gets longer.

solution:

shopping_list = ["water", "soap", "coffee"]

print(shopping_list)

shopping_list.append("soup")

print("shopping_list)


# Exercise 5

Menu System (challenge)

print("1. Play")

print("2. Settings")

print("3. Exit")

ask for input

use: 

if choice == "1" :

solution:

print("1.Play")

print("2.Settings")

print("3.Exit")

game = input("choose: 1, 2, or 3").lower()

if game == "1":

  print ("start game")

elif game == "2":

  print("Do you want to change charactes")

elif game == "3":

  print("good bye")

else:

  print("invalid")

# Exercise 6

Mini challenge

make:

Favorite Thing Generator

store:

favorite food

game 

color

music

Then randomly print one (random.choice)

solution:

favorite_thing = ["food", "games", "colors", "music"]

favorite_thing = input("do you like food, games, colors, or music").lower()

if favorite_thing == "food":

    responses = ["that sounds delicious", "yummy"]

    print(f"{random.choice(responses)}")

elif favorite_thing == "games":

    responses = ["Can you teach me to play?", "me too"]

    print(f"{random.choice(responses)}")

elif favorite_thing == "color":

    responses = ["that is a beautiful color", "i like that color too"]

    print(f"{random.choice(responses)}")

  elif favorite_thing == "music":

    response = ["hmm ok", "can you recommend a song"]

    print(f"{random.choice(responses)}")

  else:

    print("invalid")
    

# Exercise 7

Personal Introduction Machine

ask the user 

name 

age 

favorite food

favorite color

and add two more questions

then print

output example

Hello Alex!
You are 18 years old.
Sushi is delicious.
Your favorite color is blue.

solution:

print("What is your name?")

my_name = input(">")

print(f'hello, {my_name}")

print("how old are you?")

my_age = input('>')

print(f"you are {my_age} years old")

print("what is your favorite food")

favorite_food = input('>')

print(f'{favorite_food}, is delicious")

print("what is your favorite color")

my_color = input('>')

print(f"{my_color} is beautiful")

# Exercise 8

Fake Receipt Generator

Variables:

item = "Coffee"

price = 5

tax = 0.50

calculate:

total = price + tax

output:

---- Receipt ----

Item: Coffee

price: $5

tax: $ 0.50

Total: $ 5.50

solution:

print("-"*5, "Receipt", "-"*5)

item = "coffee"

price = 5

tax = 0.50

total = price + 0.50

print(f"\nitem:{item}, \nprice:{price}, \ntax{tax}, \ntotal:{total}")

# Exercise 9

Mood Energy Meter

ask: 

how are you feeling?

if the answer is 

Happy, add points 

tired, subtract points

print final energy score

---- hint use if/elif/ else ----

solution:

points = 0

print("how are you feeling today")

mood = input("happy, tired, stressed\n")

if mood == "happy":

  print("i love that for you")

  points +=10

elif mood == "tired":

  print("go to bed")

  ponts -=5

else:

  print("invalid")

print(f"total points:{points}")

# Exercise 10

Secret Number Story

ask user for a number

if correct 

print you found the magic number

exit

else 

print wrong number, try again

solution:

while True:

  print("pick a number between 1 and 10")

  number = input(">")

  if number == "4":

    print("correct")

  else:

    print("try again")

# Remember I'm still learning to code, and if you know another way to solve the exercise, that is perfectly fine. Share your method (if you like); we can all learn from it. If you see a mistake in any of the solutions, please let me know so i can fix it.



