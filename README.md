class Person:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age
        self.gender = gender

    def introduce(self):
        return f"Hi there, my name is {self.name}. I am {self.age} years old and I am {self.gender}."

person1 = Person("Salasya", 47, "male")

print(person1.introduce())
