class Person:

    head = 1
    legs = 2
    hands = 2

    def __init__(self,name,age,height,grade):
        self.name = name
        self.age = age
        self.height = height
        self.grade = grade

    def details(self):
       print("hello my name is", self.name)
       print("I am ",self.age ,"years old.")
       print("I am ",self.head,"to think and my ",slelf.legs, "to walk.")
    
    def modify(self):
        new_name = input("Enter new name")
        print("Old name:",self.name)
        self.name = new_name
        print("new name:", self.name)

p1 = Person("Agam",13,5.6,9)
p2 = Person("Daniil",13,5.1,7)
p3 = Person("Shreyan",13,5.3,9)
p4 = Person("Annie",13,5.7,7)
p5 = Person("Lulu",13,5.11,8)
