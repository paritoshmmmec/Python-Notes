# Python-Notes

## How Named tuple and why? 

from collections import namedtuple
Car = namedtuple('Car', 'make color')
car = Car(1987, "Red")
print(car.make)

namedtuple is readonly container,so cannot be modified following query will give error.
my_car.color = 'blue'
AttributeError: "can't set attribute"
