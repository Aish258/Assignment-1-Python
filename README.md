# Assignment-1-Python
basic_price=int(input("Enter the basic price of vehicle="))
weight=float(input("Enter the weight of vehicle in kilograms="))
type_of_vehicle=input("Enter the type of vehicle=")
if type_of_vehicle=="P":
    vehicle_tax=basic_price*0.05
    weight_tax=weight*0.01
    insurance_premium=basic_price*0.01
    onroad_price=basic_price+vehicle_tax+weight_tax+insurance_premium
elif type_of_vehicle=='B':
    vehicle_tax=basic_price*0.1
    weight_tax=weight*0.03
    insurance_premium=basic_price*0.02
    onroad_price = basic_price + vehicle_tax + weight_tax + insurance_premium

d1={"Type":type_of_vehicle,"Weight":weight,"Basic price":basic_price,"Vehicle tax":vehicle_tax,"Weight tax":weight_tax,"Insurance":insurance_premium,"On road price":onroad_price}
print(d1)
