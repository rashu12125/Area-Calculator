# Area-Calculator
print("==================")
print("Area Calculator 📐")
print("==================")
print("1) Square")
print("2) Rectangle")
print("3) Triangle")
print("4) Circle")
print("5) Quit")

shape = int(input("which shape : "))

if shape == 1:
    side = float(input("Enter side : "))
    square = side**2
    print("Area of Square : ",square)
    
elif shape == 2:  
    length = float(input("Enter lenght : "))
    width = float(input("Enter width: "))  
    Rectangle = length*width
    print("Area of Rectangle : ",Rectangle)
elif shape == 3:
    height = float(input("Enter height: "))
    base = float(input("Enter base : "))
    Triangle = (height*base)/2
    print("Area of Triangle : ",Triangle)
elif shape == 4: 
     π = 3.14
     radius = float(input("Enter radius : "))
     Circle = π*(radius**2) 
     print("Area of circle : ",Circle)
elif shape == 5:
    print("Goodbye!")
else:
    ("invalid input")








