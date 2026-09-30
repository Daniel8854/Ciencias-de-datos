# Ciencias-de-datos
## Ejecución del proyecto

1. Clonar el repositorio y entrar a la carpeta del proyecto.
2. Crear un entorno virtual e instalar las dependencias:

```bash
python -m venv .venv
activate
pip install -r requirements.txt
```
3. En la raíz del proyecto crear un archivo .env con la conexión a PostgreSQL:
```.env
DATABASE_URL=postgresql+psycopg2://usuario:password@localhost:5432/nombre_base
```
4. Iniciar Jupyter:
```bash
jupyter notebook
```

5. Ejecuta los notebooks en este orden:
- fase_b_etl.ipynb
- fase_c_ad.ipynb
- fase_d_visualizaciones.ipynb

6. Cuando termine la ejecución, verificar que los DataFrames y tablas se hayan cargado correctamente en la base de datos.


Los integrantes del grupo se comprometen a mantener el dataset elegido durante los tres proyectos del semestre (P1, P2/3, P4). Cambios sólo por autorización del profesor.
### *Firmas*
| SGM | DHR | SCT | JDA |