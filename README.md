# Exercise_App
 import random
Day_of_the_week =("Wednesday")
print("This is your exercise for " + Day_of_the_week)
if Day_of_the_week == "Monday":
    print(random.choice(("Bench", "Flys", "Dumbell_Raise")))
elif Day_of_the_week == "Tuesday":
    print(random.choice(("Shoulder Press", "Lat_Raises", "Face_Pull")))
elif Day_of_the_week == "Wednesday":
    print(random.choice(("Seated_Row", "Lat_Pulldown", "Bent_OverRow")))
elif Day_of_the_week == "Thursday":
    print(random.choice(("Row", "Seated_Row's", "Bent over Rows", "Lat Pulldown")))
elif Day_of_the_week == "Friday":
    print(random.choice(("Shoulder Press","Lat Raises", "Cable Pulls")))
elif Day_of_the_week == "Saturday":
    print("Rest_Day")
