# Personal-Profile-Processor
#intermidiate level
def profile():
	Name = input("Enter your full name :").title()
	Age =int(input("Enter your age :"))
	City =input("Enter your city :")
	#calculating birth year
	birth_year = 2026-Age
	#rectitying the age
	if Age<=0:
		print("Enter a valid age")
		profile()
	print(f"Hello! My name is {Name}.")
	print(f"I am {Age} year old (born in {birth_year}).",end="")
	print(f"I live in {City}.")
	if Age<=18:
		print("Just getting started")
	elif 18<Age<25:
		print("Prime time to build skills")
	else:
		print("Experience meets learning")
profile()
