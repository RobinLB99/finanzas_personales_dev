# Finanzas Personales

Una aplicación de consola para gestionar finanzas personales, incluyendo ingresos, egresos, resúmenes y gráficos.

## Características

- Registro de ingresos y egresos con categorías predefinidas.
- Visualización de resúmenes financieros totales y mensuales.
- Gráficos en consola y generados como imágenes PNG.
- Interfaz interactiva con navegación por teclado.

## Requisitos

- Python 3.8+
- Dependencias: `rich`, `prompt_toolkit`, `matplotlib`

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/ErickCosta98/finanzas_personales.git
   cd finanzas_personales
   ```

2. Crear un entorno virtual:
   ```bash
   python3 -m venv ./
   ```

3. Instala las dependencias:

   ```bash
   ./bin/pip install -r requirements.txt
   ```

4. Ejecuta la aplicación:

   ```bash
   ./bin/python -m finanzas_personales.main
   ```

## Uso

- Usa las flechas ↑/↓ para navegar por los menús.
- Presiona Enter para seleccionar una opción.
- Ingresa datos como cantidad y descripción cuando se solicite.
- Usa Escape para salir de submenús o cerrar el programa.

## Captura de Pantalla

![Menú Principal](menu_principal.png)

## Estructura del Proyecto

- `database.py`: Manejo de la base de datos SQLite.
- `graphics.py`: Generación de gráficos en consola y PNG.
- `interface.py`: Lógica de la interfaz de usuario.
- `models.py`: Definición de categorías y estructuras de datos.
- `main.py`: Punto de entrada principal.

## Contribuir
¡Las contribuciones son bienvenidas! Por favor, abre un issue o un pull request.

## Licencia

MIT
