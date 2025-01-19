# 🛢️ **¿Dónde abrir 200 nuevos pozos petroleros?**

📌 Este proyecto analiza datos geológicos para determinar las mejores ubicaciones para abrir 200 nuevos pozos petroleros. Se utilizan técnicas avanzadas de **regresión lineal** y **bootstrapping** para predecir volúmenes de reservas, evaluar beneficios y mitigar riesgos, maximizando así la rentabilidad y seguridad en la toma de decisiones.

---

## 🚀 **Objetivo del Proyecto**
Identificar la región más prometedora para abrir nuevos pozos petroleros, basada en datos históricos y predicciones de modelos, mientras se analizan riesgos y beneficios financieros.

---

## 🔍 **Pasos del Análisis**

1. **Preparación de Datos:**
   - Limpieza y exploración inicial de los datos geológicos.
   - Verificación de valores nulos e inconsistencias.
   - División de los datos en conjuntos de entrenamiento y validación.

2. **Entrenamiento del Modelo:**
   - Aplicación de modelos de **regresión lineal** para predecir los volúmenes de reservas de petróleo en diferentes regiones.
   - Evaluación del rendimiento mediante métricas como RMSE.

3. **Cálculo de Ganancias:**
   - Selección de los 200 pozos más prometedores por región.
   - Estimación de beneficios con base en las predicciones de reservas.

4. **Evaluación de Riesgos:**
   - Uso de **bootstrapping** para analizar la distribución de beneficios y el riesgo de pérdidas en cada región.
   - Cálculo de intervalos de confianza y probabilidades de riesgo.

5. **Conclusiones y Recomendaciones:**
   - Identificación de la región con el mayor potencial de beneficio ajustado por riesgo.

---

## 📊 **Resultados Principales**
- **Región 2**: Aunque muestra un beneficio promedio más alto, su rentabilidad no es financieramente viable bajo las condiciones actuales debido al alto costo de inversión.
- **Región 1**: Ofrece predicciones más precisas con menor variabilidad, ideal para estrategias conservadoras.

---

## 🛠️ **Tecnologías Utilizadas**

- **Lenguajes y Bibliotecas**:
  - Python
  - Pandas, NumPy
  - Scikit-learn

- **Métodos Estadísticos**:
  - Regresión Lineal
  - Técnicas de Bootstrapping
  - Evaluación de Métricas (RMSE, AUC-ROC)

---

## ⚙️ **Cómo Ejecutar**

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/MiguelMoc1/oil_wells_project.git
