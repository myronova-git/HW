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
            
    def remove_person(self, person: Person):
        if person in self.__people:
            print("Person remove from People")
            self.__people.remove(person)
        else:
            print("Person not found in list")
