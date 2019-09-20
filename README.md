# AREA-CICUM-OF-A-CIRCLE-USING-OOPS

class Circle:
    #class variable:
    pi = 3.14
    def __init__(self,radius):
        self.radius = radius


    #method for find circumstances of circle

    def find_circum(self):
        return 2 * Circle.pi * self.radius

    #method for find area of a circle:

    def find_area(self):
        return Circle.pi * self.radius ** 2
#object
circ1 = Circle(7)
print(circ1.find_circum())
print(circ1.find_area())
