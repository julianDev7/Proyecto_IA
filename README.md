# Proyecto IA – Análisis de Datos de Pingüinos 🐧

**Autor:** Julian Montoya  
**Repositorio:** [Proyecto_IA](https://github.com/julianDev7/Proyecto_IA.git)

---

## 📌 Descripción

Este proyecto tiene como objetivo realizar un **análisis exploratorio de datos (EDA)** sobre un dataset de pingüinos utilizando **Python** y librerías de análisis y visualización de datos.  
El dataset incluye información sobre diferentes especies de pingüinos, con variables morfométricas y biológicas relevantes.

El trabajo se desarrolla en un **notebook interactivo (`Ejemplo.pinguinos.ipynb`)**, complementado con un archivo CSV (`pinguinos.csv`) que contiene los datos.

---

## 📂 Contenido del Repositorio

- **`Ejemplo.pinguinos.ipynb`** → Notebook con el análisis paso a paso.
- **`pinguinos.csv`** → Dataset con información de pingüinos.
- **`README.md`** → Documento descriptivo del proyecto.

---

## 📊 Dataset

El archivo `pinguinos.csv` contiene las siguientes columnas:

| Columna              | Descripción |
|----------------------|-------------|
| `species`            | Especie del pingüino (Adelie, Gentoo, Chinstrap). |
| `island`             | Isla donde fue observado. |
| `culmen_length_mm`   | Longitud del pico (mm). |
| `culmen_depth_mm`    | Profundidad del pico (mm). |
| `flipper_length_mm`  | Longitud de la aleta (mm). |
| `body_mass_g`        | Masa corporal (g). |
| `sex`                | Sexo del pingüino (MALE/FEMALE). |

---

## 🛠 Librerías Utilizadas

- **pandas** → Manipulación y limpieza de datos.
- **matplotlib** → Visualización de datos en gráficos.
- **seaborn** → Visualización estadística avanzada.

---

## 🚀 Ejecución del Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/julianDev7/Proyecto_IA.git
Instalar dependencias necesarias:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Abrir el notebook:

bash
Copy
Edit
jupyter notebook Ejemplo.pinguinos.ipynb
📈 Ejemplo de Uso
python
Copy
Edit
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Cargar datos
df = pd.read_csv('pinguinos.csv')

# Vista previa
print(df.head())

# Gráfico de dispersión
sns.scatterplot(data=df, x="culmen_length_mm", y="culmen_depth_mm", hue="species")
plt.show()
📜 Licencia
Este proyecto se distribuye bajo licencia MIT.
Puedes usarlo y modificarlo libremente, citando al autor original.
