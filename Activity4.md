# Actividad 4
## Ejercicio 1
### **1. Crear una nueva rama para una caraacterística:**
- Crea una nueva rama llamada feature/advanced-feature desde la rama main:
![Imagen 1](/Image/EJ1-1.jpg)  
### **2. Modificar archivos en la nueva rama:**
- Edita el archivo main.py para incluir una función adicional
![Imagen 2](/Image/EJ1-2-1.jpg)
- Añade y confirma estos cambios en la rama feature/advanced-feature:
![Imagen 3](/Image/EJ1-2-2.jpg)  
### **3. Simular un desarrollo paralelo en la rama main:**
- Cambia de nuevo a la rama main
- Edita el archivo main.py de forma diferente (por ejemplo, cambia el mensaje del print original)
- Añade y confirma estos cambios en la rama main  
![Imagen 4](/Image/EJ1-3.jpg)
### **4. Intentar fusionar la rama feature/advanced-feature en main:**
- Fusiona la rama feature/advanced-feature en main  
![Imagen 5](/Image/EJ1-4.jpg)  
### **5. Intentar fusionar la rama feature/advanced-feature en main:**
- Git generará un conflicto en main.py. Abre el archivo y resuelve el conflicto manualmente, eligiendo cómo combinar las dos versiones.
- Después de resolver el conflicto, añade el archivo resuelto y completa la fusión  
![Imagen 6](/Image/EJ1-5-1.jpg)
### **6. Eliminar la rama fusionada:**  
![Imagen 7](/Image/EJ1-6.jpg)

## Ejercicio 2
**1. Ver el historial detallado de commits:**
- Usa el comando git log para explorar el historial de commits, pero esta vez con más detalle
![Imagen 8](/Image/EJ2-1.jpg)
**2. Filtrar commits por autor:**
- Usa el siguiente comando para mostrar solo los commits realizados por un autor específico:
![Imagen 9](/Image/EJ2-2.jpg)
**3. Revertir un commit:**
- Imagina que el commit más reciente en main.py no debería haberse hecho. Usa git revert para revertir ese commit:
![Imagen 10](/Image/EJ2-3.jpg)
**4. Rebase interactivo:**
- Realiza un rebase interactivo para combinar varios commits en uno solo. Esto es útil para limpiar el historial de commits antes de una fusión.
- Usa el siguiente comando para empezar el rebase interactivo:
  $ git rebase -i HEAD~3
![Imagen 10](/Image/EJ2-4-1.jpg)
