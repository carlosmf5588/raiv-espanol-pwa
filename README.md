# RAIV Español - PWA pública v11

La aplicación pública no contiene los textos privados de RAIV, el inventario de cartas de Despliegue ni las cartas del Mazo de Misiones Imperiales. Todo ese contenido se importa desde `RAIV_datos_privados_v11.json` y permanece en el dispositivo.

## Cambios de v11
- Nuevo **Mazo de Misiones Imperiales** con las 8 cartas físicas identificadas.
- `Cambio de Prioridad` roba automáticamente una misión sólo si no hay otra Misión Imperial en juego.
- `Planes Saboteados` puede añadir otra misión aunque ya haya una activa.
- Las 6 misiones secundarias y 2 obligatorias quedan diferenciadas.
- Si una misión secundaria Imperial es ignorada porque se juega otra secundaria, la app puede aplicar su recompensa RAIV:
  - desbloqueo de Darth Vader o El Gran Inquisidor cuando corresponde;
  - o +1 Plan Secreto si la recompensa no es de Despliegue.
- Controles manuales de respaldo para ambos tipos de robo.
- En Despliegue:
  - grupos abiertos y amenaza usan controles `− / +`;
  - las cartas se ordenan por facción y alfabéticamente;
  - las variantes élite se muestran en rojo;
  - `Prioridad de Estatus` pasa a llamarse `¿Qué toca en Estatus?`;
  - los intentos fallidos de despliegue muestran un aviso más visible.
- Se conserva la migración de guardados de v10.

Para actualizar desde v10, sustituye los archivos públicos del repositorio por los de este ZIP e importa una vez `RAIV_datos_privados_v11.json` en cada dispositivo/navegador que uses.
