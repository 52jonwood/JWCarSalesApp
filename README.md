# JWCarSalesApp
CarSales App Intro to Programming
# start car buying menu
print("Welcome to Jon's Car Shop!")

vehicleType = int(input("Do you want to buy a car [1] or truck [2]"))
if vehicleType == 1:
    basePrice = 1000
elif vehicleType ==2:
    basePrice = 2000
else:
    print("Please enter a 1 or 2")
    exit()
