# Clasificador de Propinas para Viajes en Taxi en NYC (2020)

## Descripción del Proyecto

Este proyecto utiliza datos de viajes de taxis amarillos en Nueva York para desarrollar un modelo de machine learning que predice si un viaje tendrá una propina superior al 20% del precio del viaje. El análisis incluye la comparación del rendimiento del modelo mes a mes y pre-pandemia vs post-pandemia. Este repositorio sigue las buenas prácticas de desarrollo vistas en el curso.

## Estructura del Repositorio

```
├── src/
│   ├── data_processing.py    # Scripts para cargar y procesar datos
│   ├── model_training.py     # Script para entrenar y evaluar el modelo
│   └── utils.py              # Funciones auxiliares
├── notebooks/
│   ├── 00_nyc_taxi_model.ipynb   # Notebook principal con el análisis
│   └── 01_analysis_pre_post_pandemic.ipynb # Notebook con la comparación pre/post-pandemia
├── data/
│   └── (datos crudos y procesados, no incluidos en el repo público)
├── tests/
│   └── test_data_processing.py  # Pruebas unitarias para el procesamiento de datos
├── README.md
├── requirements.txt  # Dependencias del proyecto
└── .gitignore        # Archivos y carpetas ignoradas por git
```

## Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Liser1979/tarea-taxi-model.git
   cd tarea-taxi-model
   ```

2. **Crea un entorno virtual:**
   ```bash
   python3 -m venv env
   source env/bin/activate  # En Windows usa `env\Scriptsctivate`
   ```

3. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

## Uso

### 1. Preparación de los Datos

Ejecuta el script para cargar y procesar los datos:

```bash
python src/data_processing.py
```

### 2. Entrenamiento del Modelo

Entrena el modelo con los datos procesados:

```bash
python src/model_training.py
```

### 3. Ejecución del Notebook

Para ejecutar el análisis completo, abre y ejecuta el notebook principal:

```bash
jupyter notebook notebooks/00_nyc_taxi_model.ipynb
```

### 4. Comparación Pre/Post Pandemia

Para analizar el rendimiento del modelo antes y después de la pandemia:

```bash
jupyter notebook notebooks/01_analysis_pre_post_pandemic.ipynb
```

## Resultados

Los gráficos generados muestran cómo el modelo se comporta de manera diferente mes a mes y entre los periodos pre-pandemia y post-pandemia. Las conclusiones clave se pueden encontrar al final de cada notebook.

## Contribuciones

¡Las contribuciones son bienvenidas! Siéntete libre de abrir un issue o enviar un pull request.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

## Créditos

Este proyecto fue desarrollado como parte de un curso de análisis de datos. Agradecemos a los creadores de los datos de taxi de la ciudad de Nueva York y a todos los desarrolladores de las bibliotecas de Python utilizadas en este proyecto.


## Contacto

Para cualquier pregunta, por favor contacta a Ariel Gonzalez (a.gonzalezl@udd.cl)
