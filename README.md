# Ejercicio en el que, a partir de un seudo codigo, desarrollo totalmente solo, un modelo ML
### Pasos
- Defir el problema a resolver
- Importar librerias requeridas
- Obtener el dataset para entrenar y probar el modelo
- Realizar el análisis exploratorio de los datos
- Definir si se requiere una ingenieria de atributos o variables (Feature engineering)
- Crear , entrenar y probar modelo
- Evaluar modelo
- Validación con Cross Validation
### Problema: Crear un modelo que pueda predecir valores a partir de una sola variable numérica independiente
- Crear un data set numérico con cierto ruido que se ajuste a una distribución polinómica y verificar gráficamente
- Probar comportamiento con un dataset de prueba
- El método de evaluación sera MSE, R2_Score. Confirmación con Cross_Validation
## Conclusiones
- Se ha visualizado que la transformación de variables independientes (features) a variables polinomiales ayuda a obtener predicciones mas acertadas.
- El uso de variables polinomiales de grado 2 es suficiente para resultados aceptables. Se obtuvo R2=0.96, es decir una excelente fiabilidad para las previsiones futuras. Es decir, en el 96% de los casos la variación de la variable dependiente es correctamente explicada por la variación de las variables independientes.
- Finalmente, se confirma lo aseverado al validar el modelo con 5 (k=5) grupos diferentes de datos de entrenamiento y pruebas.
