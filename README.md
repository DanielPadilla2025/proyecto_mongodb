# Proyecto MongoDB - Signos Vitales

Este proyecto es parte de la actividad de Big Data, donde trabajé con MongoDB para almacenar y consultar datos de signos vitales de pacientes.  

## Estructura del proyecto

- `data/` → contiene el CSV con los datos (`datos_signos_20000.csv`).  
- `scripts/` → scripts de Node.js para:  
  - `database.js` → carga datos en MongoDB  
  - `consultas_basicas.js` → consultas básicas (insertar, actualizar, eliminar, seleccionar)  
  - `consultas_agregacion.js` → consultas de agregación (contar, sumar, promedio, estadísticas)  
- `capturas/` → capturas de pantalla de los resultados de las consultas.  
- `.gitignore` → archivos/carpetas ignorados: `node_modules`, `package-lock.json`, `.DS_Store`, `data/`, `capturas/`.

## Descripción de mi trabajo

1. Creé la base de datos `signos_vitales` y la colección `signos_vitales`.  
2. Inserté los 20,000 registros del CSV de prueba.  
3. Implementé consultas básicas: inserción, selección, actualización y eliminación.  
4. Implementé consultas con filtros y operadores.  
5. Implementé consultas de agregación para estadísticas: contar registros, promedio de temperatura, cantidad por medicamento.  
6. Documenté los resultados y capturé pantallas de las consultas exitosas.  

