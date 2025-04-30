# Actividad - Trabajando con DataFrames de Pandas

Este proyecto consiste en crear una conexión con un dataset y trabajar con un conjunto de datos utilizando **Pandas** en Python. Se realizan diversas actividades para analizar y manipular los datos, siguiendo criterios de evaluación específicos.

## Estructura del Proyecto

- **`actividad_df.ipynb`**: Cuaderno de Jupyter donde se desarrollan las actividades.
- **`Salaries.sqlite`**: Base de datos SQLite utilizada como fuente de datos.
- **`Salaries.csv`**: Archivo CSV generado al exportar los datos procesados.
- **`requirements.txt`**: Archivo con las dependencias necesarias para ejecutar el proyecto.

## Actividades Realizadas

1. **Top 10 empleados con mayor salario total (incluyendo beneficios)**:
   - Se extraen y muestran los 10 empleados con mayor salario total.

2. **Filtrar empleados con más de 50,000 en horas extra**:
   - Se filtran los empleados cuya columna `OvertimePay` supera los 50,000.

3. **Contar cuántos empleados únicos hay por año**:
   - Se agrupan los datos por año y se cuenta el número de empleados únicos.

4. **Ver cuántos cargos únicos existen y los 5 más comunes**:
   - Se calcula el número de títulos de trabajo únicos y se muestran los 5 más frecuentes.

5. **Mostrar el salario total promedio por año**:
   - Se calcula el salario total promedio agrupado por año.

6. **Exportar los datos a un CSV y mostrar los últimos 10 valores**:
   - Se exportan los datos procesados a un archivo CSV y se verifican los últimos registros.

## Requisitos

- Python 3.7 o superior
- Dependencias listadas en `requirements.txt`

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/GastonFlorenciano/pandas_df_tlp3_Gaston_Florenciano.git
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Abre el archivo `actividad_df.ipynb` en Jupyter Notebook o JupyterLab.  
2. Ejecuta las celdas en orden para realizar las actividades.

## Nota

- Asegúrate de que el archivo `Salaries.sqlite` esté en el mismo directorio que el cuaderno de Jupyter.