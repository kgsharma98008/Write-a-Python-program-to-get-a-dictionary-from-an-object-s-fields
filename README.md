# Write-a-Python-program-to-get-a-dictionary-from-an-object-s-fields

class Person:
 def __init__(self, name, age, city):
 self.name = name
 self.age = age
 self.city = city
person = Person("John", 30, "New York")
person_dict = vars(person)
print("The dictionary created from the object's fields is:", person_dict)
