# Reto-3-Diego-Reyes.
Algoritmo para la obtención de divisores de un número n.
1. Diagrama de flujo.

https://app.diagrams.net/#G1B2GF00noq7FS_y4OjLJdlOm4SehHOZ_M#%7B%22pageId%22%3A%22MqRyTdFlWXpdY8rp7Vmq%22%7D
2. Pseudocódigo


Inicio
    Definir lista_divisores como una lista vacía
    Leer n  // Número del cual queremos encontrar divisores

    // Paso 1: Crear una lista de números naturales desde 2 hasta n/2
    Para i desde 2 hasta (n / 2) Hacer:
        // Paso 2: Verificar si i es divisor de n
        Si (n % i == 0) Entonces:
            Añadir i a lista_divisores  // Agregar a la lista de divisores

    Fin Para

    // Paso 3: Mostrar los divisores encontrados
    Mostrar "Los divisores de", n, "son:", lista_divisores
Fin
