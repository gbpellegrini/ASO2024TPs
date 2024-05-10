# ARQ Y SO - TP N3

1. 
    - a) Realice una media de 10 ejecuciones, y como resultado obtuve un promedio de 4.056 seg para el programa conhilos, y una media de 5.18 para sinhilos. Claramente notamos que el proceso sinhilos, tarda mas en terminar su ejecucion.

    - b) 
        ### Mis tiempos
        - conhilos: 4.056
        - sinhilos: 5.18

        ### Tiempo compañero
        - conhilos: 4.06
        - sinhilos: 5.19
        
        Si bien son diferentes, no varian ampliamente a los mios.
    
    - c) Podemos notar que el tiempo aumento de 0.012 seg a 3.11 y el resultado paso de ser 0 a numeros aletorios mayores que 0. Al descomentar las lineas 11,12,19,20 alteramos los procesos de los hilos, haciendo asi que tengan que esperar mas tiempo para ejecutarse, y como no tenemos ningun semaforo o estructura que nos permita evitar una race condition, un hilo se ejecuta mas rapido que otro, generando asi diversos resultados en la variable "acumulador".

2. 
    - b)  
