class Estudiante():
    def __init__(self, nombre, nota):
        self.nombre = nombre
        self.nota = nota

    def imprimir(self):
        print(f"Nombre: {self.nombre} \nNota: {self.nota}")

    def resultados(self):
        if self.nota >= 7:
            print("Has APROBADO!")
        else:
            print("Has REPROBADO!")

estudiante1 = Estudiante("Adrian", 6)
estudiante1.imprimir()
estudiante1.resultados()

estudiante2 = Estudiante("Cristian", 8)
estudiante2.imprimir()
estudiante2.resultados()

![image](https://github.com/user-attachments/assets/efcd79c3-4804-4b80-b393-bc19ec4e82a4)
![image](https://github.com/user-attachments/assets/21674045-14f6-4850-9418-11f4a426caa5)
