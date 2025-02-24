# 🚢 ¡Desafío del Titanic: Descubre los Supervivientes! 🚢
## Introducción
¡Bienvenidos a bordo del RMS Titanic! En este emocionante proyecto, nos convertimos en detectives históricos para desentrañar el misterio de la supervivencia en uno de los naufragios más famosos de la historia. Utilizando técnicas de Machine Learning y un toque de creatividad, analizaremos datos y descubriremos los patrones que determinaron quién abordó los botes salvavidas.

## 🚀 Objetivos
- Investigar patrones de supervivencia en los pasajeros del Titanic.
- Aplicar técnicas de Machine Learning para predecir la supervivencia.
- Evaluar el rendimiento de distintos modelos y mejorar su precisión.

## 📌 Hallazgos Importantes:

✔️ Las mujeres tenían muchas más probabilidades de sobrevivir que los hombres. 
✔️ Los pasajeros de 1ª clase tenían más chances de sobrevivir que los de 3ª clase.

## 🕵️‍♂️ Pasos del Proyecto
### 1. Selección de Modelos
Eligir la herramienta de detective favorita: regresión logística, árboles de decisión, bosques aleatorios, entre otros. Cada modelo tiene sus fortalezas y debilidades.

### 2. Entrenamiento del Modelo
Seleccionar y entrenar tu modelo de aprendizaje automático. Ajustar los parámetros para mejorar su precisión. 
Ejemplo de código:
```
# Entrenar modelo
model = RandomForestClassifier(n_estimators=100, random_state=42)
model.fit(X_train, y_train)
```
### 3. Evaluación del Modelo
Evaluar el rendimiento utilizando métricas como la precisión, exactitud y la matriz de confusión. 
Ejemplo de código:
```
# Evaluación del modelo
y_pred = model.predict(X_val)
accuracy = accuracy_score(y_val, y_pred)
print(f'Precisión del modelo: {accuracy}')
```
### 4. Visualización de Datos
Creados gráficos para visualizar la supervivencia por clase socioeconómica y edad.

### 5. Generar Predicciones
Usa el modelo para predecir en el conjunto de test y guarda los resultados.

## 🔮 Resumen de Hallazgos
- Género y supervivencia: Las mujeres tuvieron una mayor tasa de supervivencia que los hombres.
- Clase socioeconómica y supervivencia: La probabilidad de sobrevivir fue mayor para las personas en primera clase.
- Edad y supervivencia: Los niños pequeños tuvieron una mayor tasa de supervivencia.

## 🏷️ Licencia
Este proyecto está bajo la licencia MIT. Consulte el archivo de LICENCIA para obtener más detalles.
