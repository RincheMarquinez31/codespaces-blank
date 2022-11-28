# Python Classes

class Person:
    def __init__(slef,name):
        slef.name = name

    def say_hello(self):
        print("Hello {}!".format(self.name))

Rinche = Person('Rinche')
Rinche.say_hello()
