#Distance Calculator
##Calculates the distance between variables
import math

x1 = float(input("Point 1: "))
x2 = float(input("Point 2: "))
y1 = float(input("Point 3: "))
y2 = float(input("Point 4: "))

distance = math.sqrt((x2-x1)**2 + (y2-y1)**2)

print(f"Distance: {distance:.2f}")
