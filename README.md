# Análisis de Datos -IBM Quantum
Este proyecto realiza un análisis estadístico y de rendimiento sobre un conjunto de datos (*dataset*) de **IBM Quantum** obtenido de kaggle. El objetivo principal es evaluar el rendimiento, ruido y estabilidad de los cúbits de un procesador cuántico.

# Resultado del Análisis 
**Promedio general del T1:**132.25 us 
**Promedio general del T2:**104.25 us 

**Cúbits estables encontrados:** 33 (superan el promedio)

## Los 5 cúbits más ruidosos (menor T1):

| Cúbit  | T1 (us) |
| :---:  |  :---: |
| 55 |  2,06   |
| 121  |   2,31  |
| 100  |   30,71  |
|  86 |   37,34  |
|  98 |   39,43  |

# Nota: Los cúbits 55 y 121 son los más críticos al tener tiempos de retención extremadamente bajos #




