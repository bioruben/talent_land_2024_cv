# talent_land_2024_cv

# Computer Vision y Realidad Aumentada - Talent Land 2024

Material utilizado en en el workshop de Talent Land el 03/04/2024.

## Instalar dependencias necesarias

Las versiones de las dependencias utilizadas cuando se realizaron estos demos son:

- Python 3.7.3
- OpenCV 4.6.0
- Para usar los marcadores es necesario tener la versión de contrib de OpenCV:

``` pip install opencv-contrib-python ```


## Codes

- generate_aruco.py

	Permite generar los marcadores para su impresión de acuerdo a su código.

- detect_aruco.py

	Permite detecta los marcadores y que tiene un flag para detectar los pokemones.

## Usage

Todos los códigos tienen un menú de help para poderlo correr, ejemplo:

```python3 detect_aruco.py -h```

Si se desea activar el flag para desplegar a los pokémon.

```python3 detect_aruco.py -p True```