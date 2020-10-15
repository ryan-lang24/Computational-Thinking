# Computational-Thinking

@author: ryanlang
"""

class Ellipse(object):
    def__init__(self, a , b):
        self.min_radius = a
        self.maj_radius = b
    
    def area(self, other):
        get_area = (self.min_radius * self.maj_radius * 3.14159)
    
    def perimeter(self,other):
        get_perimeter = (2 * 3.14159 * ((self.min_radius + self.maj_radius)**.5) / 2)
        
new_elli = Ellipse(10,17)
area = new_elli.get_area()
perimeter = new_elli.get_perimeter()

print(f'"This ellipse has an area of" , get_area, "and a perimeter of", get_perimeter)
