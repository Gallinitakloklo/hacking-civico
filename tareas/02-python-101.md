#La densidad poblacional nos permite saber que tan concentrada o dispersa se encuentra la población. Es una relación entre la cantidad de personas que viven en un lugar
#y la extensión del espacio que habitan.
#La densidad poblacional se obtiene dividiendo el número de habitantes entre el área donde viven.

def densidad_poblacion():
    densidadpoblacional = poblacion / area_ciudad
    print(f"La densidad poblacional es {densidadpoblacional}")
    return

#Ejemplo de resultado
poblacion = 119938473
area_ciudad = 1964375
densidad_poblacion()

