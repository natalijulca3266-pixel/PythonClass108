# PythonClass108





total_bill = 0.00
while True:
    print("Welcome to The Cafe Kiosk. Here is the Menu")
    print("1. Black Coffee - $3.50")
    print("2. Plain Latte - $4.00")
    print("3. Strawberry Refresher - $5.00")
    print("4. Checkout")
    user_input = int(input("Plese select an option:")) 


    if user_input == 1:
        price = 3.50
        total_bill += price
        print("Black Coffee. Total Amount - $3.50")
        
    elif user_input == 2:
        price = 4.00
        total_bill += price
        print("Plain Latte. Total Amount - $4.00")
        
    elif user_input == 3:
        price = 5.00
        total_bill += price
        print ("Strawberry Refresher. Total Amount - $5.00")
        
    elif user_input == 4:
        print("Thank You for coming to The Cafe Kiosk! Your Total Bill is $",{total_bill}, "Hope to see you again soon!")
        break
    else:
        print("Unfortunately. That option is not on the menu. Please choose something else.")
