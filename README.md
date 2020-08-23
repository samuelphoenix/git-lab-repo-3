#covid-19
if str(input("Are you a cigarette addict older than 75 years old? ")).title().strip() == "Yes":
age=True
else:
age=False
if str(input("Do you have a severe chronic disease? ")).title().strip() == "Yes":
chronic=True
else:
chronic=False

if str(input("Is your immune system too weak? ")).title().strip() == "Yes":
immune=True
else:
immune=False

risk= age or chronic or immune

if risk:
print("You are in risky group")
else:
print("You are not in risky group")

