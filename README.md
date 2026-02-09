# 📊 ANÁLISIS DE EVASIÓN DE CLIENTES

## 📌 Descripción del proyecto
Este proyecto tiene como objetivo analizar la **evasión de clientes** a partir de un conjunto de datos de Telecom X.
Mediante análisis exploratorio y visualización de datos, se identifican patrones clave que explican por qué los clientes abandonan el servicio, con el fin de apoyar la toma de decisiones estratégicas.

El enfoque es **práctico, claro y académico**, siguiendo buenas prácticas de análisis de datos y visualización.

## 📑 Tabla de contenido
1. Descripción del proyecto  
2. Objetivo  
3. Tecnologías utilizadas  
4. Desarrollo del proyecto  
5. Resultados e insights clave  
6. Conclusión y Recomendaciones
7. Autor

## 🎯 Objetivo
- Analizar el comportamiento de evasión de clientes.
- Identificar variables y compararlas con la evasión.
- Visualizar patrones mediante gráficos claros y comprensibles.
- Generar recomendaciones de valor para la toma de decisiones.

## 🛠️ Tecnologías utilizadas
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)


## 🧩 Desarrollo del proyecto
El proyecto se desarrolló siguiendo una estructura lógica y ordenada:

1. **Carga y revisión de datos**
   - Revisión de columnas, tipos de datos y valores faltantes.
   - Identificación de variables.

2. **Manejo de incoherencias**
   - Solución de inconsistencias
   - Creación de columnas
   - Estandarización de datos

3. **Análisis de datos**

   -Se genera la información para generar gráficas, distribución de evasión.
   <p align="center">
     <img src="graficas/distribucion_de_evasion_de_clientes.png" width="35%" />
   </p>     
   - Comparación de Evasión con: Género, Tipo de Contrato y Método de pago como variables categóricas.
   <p align="center">
    <img src="graficas/evasion_por_genero.png" width="35%" />
    <img src="graficas/evasion_por_tipo_de_contrato.png" width="35%" />
    <img src="graficas/evasion_por_metodo_de_pago.png" width="35%" />
    </p>
   - Comparación de Evasión con: Antiguedad promedio, Cargo Mensual y Según permanencia (en 2 años)
        <p align="center">
    <img src="graficas/antiguedad_promedio.png" width="35%" />
    <img src="graficas/cargo_mensual_promedio.png" width="35%" />
    <img src="graficas/evasion_meses_de_permanencia.png" width="35%" />
      </p>
   - Comparación con cuentas diarias y análisis de matriz de correlación.
     <p align="center">
    <img src="graficas/cuentas_diarias_y_evasion.png" width="35%" />
    <img src="graficas/matriz_correlacion.png" width="35%" />
    </p>

## 📈 Resultados e insights clave
- Los contratos **mensuales** presentan mayor evasión comparados con contratos anuales o bienales.
- La **antigüedad promedio** de los clientes que evaden es menor.
- El **cargo mensual promedio** es más alto en clientes que abandonan el servicio.
- El **método de pago** influye en la evasión.
- Algunas variables muestran correlación directa con la evasión, lo que permite priorizar acciones preventivas.

## ✅ Conclusión y Recomendaciones
El análisis muestra que la evasión se concentra en los primeros meses, especialmente en clientes con contratos mensuales y cargos elevados, mientras que los pagos automáticos y mayor antigüedad favorecen la permanencia.
Factores como el género no influyen de forma relevante, por lo que la retención debe enfocarse en el comportamiento del cliente, el valor percibido y el monitoreo temprano de patrones de riesgo.

  -Optimizar la fidelización temprana: Crear programas de bienvenida, seguimiento personalizado y beneficios en los primeros 3–6 meses para reducir la evasión inicial.
  -Segmentar según tipo de contrato y cargo mensual: Incentivar contratos de mayor duración y ofrecer planes ajustados a la capacidad de pago del cliente para minimizar cancelaciones por percepción de alto costo.
  -Promover métodos de pago automáticos: Facilitar la suscripción recurrente mediante débitos automáticos y recordatorios digitales para aumentar la retención.

## 👩‍💻 Autor
**Proyecto realizado por: Ing. Fernanda Torres** 
<p>
GitHub: https://github.com/Maffert
</p>
