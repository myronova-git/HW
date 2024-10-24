from Person import Person


class People:
    def __init__(self):
        print("zazazazza")

        print("hello")

        self.__people = []


    def add_person(self, person:Person):
        self.people.append(person)

    def delete_person(self, person:Person):
        if self.people in person:
            self.people.remove(person)
        else:
            print("Person not found in list")
            
    def add_person(self, person: Person):
        self.__people.append(person)

    def remove_person(self, person: Person):
        if person in self.__people:
            self.__people.remove(person)
        else:
            print("Person not found in list")
