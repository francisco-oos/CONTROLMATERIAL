# CONTROLMATERIAL — Respaldo de automatizaciones Python / Excel

Archivo de **código fuente histórico recuperado sin refactorizar** desde [`francisco-oos/dev-Francisco`](https://github.com/francisco-oos/dev-Francisco), respetando los nombres y rutas originales.

## Herramientas resguardadas

- `INTERFAZ DE HERRAMINETAS/lanzador_herramientas.py`: interfaz que descubre y ejecuta scripts agrupados por carpetas.
- `INTERFAZ DE HERRAMINETAS/DATOS GESTORIA/cruce_gestoria_multicapa.py`: cruces geográficos y actualización de hojas de Excel conservando formato.
- `INTERFAZ DE HERRAMINETAS/DATOS GESTORIA/rellenar_coordenadas_csv.py`: conciliación Excel / CSV para completar coordenadas.
- `INTERFAZ DE HERRAMINETAS/TENDIDO/cruce_tendido_ft_dañado.py`: cruces y búsqueda de series en reportes de tendido.
- `Insepeccionar-Dictamen-tecnico.py`: revisión de Excel y evidencias de dictamen técnico.
- `Update_robados.py`: actualización de información a partir de registros de equipos.
- `List_Process.py`: procesamiento y exportación a Excel con OCR de imágenes/PDF.
- `utm_a_direccion_excel.py`: geocodificación inversa con Nominatim a partir de coordenadas.
- Los dos scripts `cruce_*` de la raíz se conservan como copias históricas independientes tal como estaban en el origen.

## Dependencias identificadas

Python 3 + `openpyxl`, `pandas`, `shapely`, `tqdm`, `requests`, `pyproj`, `pillow`, `opencv-python`, `pytesseract`, `numpy` y `pdf2image`, **según la herramienta elegida**. `tkinter` suele venir con la instalación de Python para Windows. Las herramientas de OCR pueden requerir además Tesseract y Poppler instalados en el equipo.

## Uso y precauciones

- Es un **respaldo de código histórico**, no una publicación certificada para producción: no se han ejecutado pruebas funcionales de todos los programas.
- Los originales en `dev-Francisco` no fueron alterados.
- Trabaja sobre una **copia de las hojas Excel/CSV** antes de ejecutar herramientas que guardan o sobrescriben archivos.
- No subir aquí datos reales de empleados, equipos, operaciones o documentos internos.
- Revisar licencias, propiedad intelectual y confidencialidad del código antes de reutilizarlo comercialmente.

Recuperado y organizado en octubre de 2026 para conservar el portafolio de automatización.
