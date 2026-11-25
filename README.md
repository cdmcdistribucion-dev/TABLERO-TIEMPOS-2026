# Tablero de Control de Tiempos · CD Mercado Central

Tablero web (un solo `index.html`) para analizar los tiempos de distribución del CD Mercado Central. Se ingresa con usuario y contraseña.

1. **Cargar bases** – subida de bases en Excel o CSV, por mes o varios meses juntos (los meses que se suben reemplazan a los anteriores, sin duplicar filas). Incluye diagnóstico de cobertura y calidad de datos.
2. **Base de tiempos** – una fila por planilla con los tiempos de pre ruta.
3. **Pre ruta** – fichada → salida del CD: Team Room, checklist, carga, encierro y geocercas.
4. **En ruta** – BEES Deliver (data 71 y 72), SIC, romaneio y Geotab: atención, desplazamiento, paradas, reagendamientos y km plan vs. real.
5. **Post ruta** – tiempo interno: descarga, gatera, portería y financiero.
6. **Árbol de tiempos** – real vs. target y plan.
7. **Jornada laboral** – jornada por chofer entre el molinete de entrada y el de salida.

## Datos
El repositorio no contiene datos. Las bases se suben desde la pestaña **Cargar bases** y quedan guardadas solo en el navegador de cada usuario (IndexedDB); no se envían a ningún servidor.
