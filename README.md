# RAIV Español - PWA pública v12

La aplicación pública no contiene los textos privados de RAIV, el inventario de cartas de Despliegue ni las cartas del Mazo de Misiones Imperiales. Todo ese contenido se importa desde `RAIV_datos_privados_v12.json` y permanece en el dispositivo.

## Correcciones de v12
- Repara automáticamente el caso de migración de v11 en el que el **Mazo de Misiones Imperiales** podía quedar guardado como 0/0/0. Si hay una campaña activa y las 8 cartas están disponibles, vuelve a crear y barajar el mazo sin tocar el resto de la campaña.
- La pestaña pasa a llamarse **Misiones Imperiales**.
- El botón de consulta de la fase pasa a llamarse **Fase de Estatus**.
- En los selectores de Despliegue, las cartas **únicas** se muestran en rojo, igual que las élite.
- Se repara la indexación completa de las 26 Cartas de Misión de **Waves 1–7**, emparejando anverso y reverso por página. Esto corrige `Acorralado` y las demás entradas cuyo título había quedado sustituido por una línea de evento.
- Se conserva la migración de guardados y los datos de campaña de versiones anteriores.

Para actualizar desde v11, sustituye los archivos públicos del repositorio por los de este ZIP e importa una vez `RAIV_datos_privados_v12.json` en cada dispositivo/navegador que uses.
