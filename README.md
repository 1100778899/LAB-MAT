# Laboratorio Matemático (LAB-MAT)

Repositorio base de juegos y simuladores interactivos de Matemática para uso en clases.

**Página de juegos:** https://1100778899.github.io/LAB-MAT/

## Estructura del proyecto

- `index.html`: portada y menú principal de los cuatro juegos.
- `juegos/operatoria.html`: Operatoria combinada.
- `juegos/prismas.html`: Prismas y redes.
- `juegos/despeja.html`: Despeja la X.
- `juegos/sistemas.html`: Sistemas de ecuaciones.
- `laboratorio-matematico.html`: copia de la portada para conservar enlaces compartidos anteriormente.

Los cuatro juegos funcionan en archivos HTML independientes. La portada los abre dentro de la misma página mediante `iframe`, sin modificar su interfaz. Para utilizarlos sin conexión, es necesario conservar los archivos correspondientes en el dispositivo.

## Privacidad

Los juegos no solicitan nombres ni envían respuestas a un servidor propio. Los resultados o contadores se mantienen durante la sesión de uso. GitHub Pages, como proveedor de alojamiento, puede registrar datos técnicos de las visitas.

## Actualizaciones

Para modificar un juego, se edita únicamente su archivo dentro de `juegos/`. Para añadir otro, se incorpora el HTML y una tarjeta enlazada en la portada. GitHub conserva el historial de versiones para poder revertir cambios.
