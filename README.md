# Love-calculator
calculate your lover love 
print("Welcome to the love calculator!")
boy_name = input("Enter boy name.")
girl_nme = input("Enter girl name.")

combined_names = boy_name + girl_nme
lower_names = combined_names.lower()

t = lower_names.count("t")
r = lower_names.count("r")
u = lower_names.count("u")
e = lower_names.count("e")
first_digit = t+r+u+e

l = lower_names.count("l")
o = lower_names.count("o")
v = lower_names.count("v")
e=lower_names.count("e")
second_digit = l+o+v+e

score = int(str(first_digit) + str(second_digit))

if (score <10) and (score >90):
    print(f"your love score is {score}.")
elif (score >=40) and (score <=50):
    print(f"your score is {score},you are alright together.")
else:
    print(f"your score is {score}")         
