# Memorias-Estaticas
class memoriaEst:
    def __init__(self):
        self.calificaciones = []

    def capturar_calificaciones(self):
        for i in range(5):
            calificacion = int(input(f"Captura la calificación {i+1}: "))
            self.calificaciones.append(calificacion)

    def mostrar_calificaciones(self):
        print("Calificaciones capturadas:")
        for i, calificacion in enumerate(self.calificaciones):
            print(f"Calificación {i+1}: {calificacion}")

def main():
    est_datos = memoriaEst()
    est_datos.capturar_calificaciones()
    est_datos.mostrar_calificaciones()

if __name__ == "__main__":
    main()
