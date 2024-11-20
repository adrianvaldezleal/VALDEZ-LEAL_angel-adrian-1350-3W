print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

class Persona:
    def __init__(self, n, e):
        self.nombre = n
        self.edad = e

    def cumpleaños(self):
        self.edad += 1

p = Persona(input("Ingrese nombre: "), int(input("Ingrese edad: ")))

p.cumpleaños()
p.cumpleaños()

print(f"{p.nombre} cumple {p.edad} años")

![image](https://github.com/user-attachments/assets/5a222b5a-fe6a-46eb-adb5-82187096360c)
![image](https://github.com/user-attachments/assets/9c918e6f-45ff-448e-a1dc-8c1b19d15ff9)

