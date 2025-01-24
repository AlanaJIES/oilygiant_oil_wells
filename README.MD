# Proyecto 10: Análisis de sitios para pozos de petróleo - OilyGiant

## Descripción
Este proyecto tiene como objetivo identificar los mejores lugares para que la empresa **OilyGiant** abra 200 nuevos pozos de petróleo. Utilizamos datos geológicos y técnicas de aprendizaje automático para analizar y predecir la productividad de diferentes ubicaciones.

## Contenido del Notebook
El notebook consta de **34 celdas**, distribuidas de la siguiente manera:
- **19 celdas de markdown:** Documentación y explicaciones detalladas del proyecto.
- **15 celdas de código:** Implementación del análisis y modelado.

### Bibliotecas principales utilizadas
El proyecto hace uso de varias bibliotecas de Python para procesamiento y aprendizaje automático, incluidas:
- **Manipulación de datos:** `pandas`, `numpy`.
- **Preprocesamiento:** `StandardScaler`.
- **Preparación del modelo:** Herramientas de `sklearn.model_selection` 
- **Modelado:** `LinearRegression`.
- **Evaluación de modelos:** Métricas como `mean_squared_error`.


## Proceso del Análisis
1. **Carga de datos:**
   - Lectura de datos relacionados con las propiedades geológicas de las ubicaciones.

2. **Preprocesamiento:**
   - Estandarización de variables mediante `StandardScaler`.
   - División de datos en conjuntos de entrenamiento y prueba con `train_test_split`.

3. **Modelado:**
   - Entrenamiento de un modelo de regresión lineal (`LinearRegression`) para predecir la productividad de los pozos.

4. **Evaluación del modelo:**
   - Métrica principal: Error cuadrático medio (MSE).

## Requisitos del sistema
Para ejecutar este notebook, necesitarás:
- Python 3.7 o superior
- Dependencias listadas en `requirements.txt`

## Ejecución
1. Clona este repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```

2. Cambia al directorio del proyecto:
   ```bash
   cd <nombre-del-directorio>
   ```

3. Abre y ejecuta el notebook:
   ```bash
   jupyter notebook proyecto_10.ipynb
   ```

## Resultados esperados
Al finalizar el análisis, se obtendrá una lista de las ubicaciones con mayor productividad estimada, lo que permitirá a **OilyGiant** tomar decisiones basadas en datos.

## Contribuciones
Si deseas contribuir:
1. Realiza un fork del repositorio.
2. Crea una rama para tus cambios:
   ```bash
   git checkout -b mejora-analisis
   ```
3. Envía un pull request explicando tus cambios.

## Licencia
Consulta el archivo `LICENSE` para más información sobre el uso y distribución de este proyecto.
