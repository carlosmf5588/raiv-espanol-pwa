# RAIV Español - PWA pública v14.1

La aplicación pública no contiene los textos privados de RAIV, el inventario de cartas de Despliegue, el Mazo de Misiones Imperiales ni las imágenes de las Cartas IA. Todo ese contenido permanece únicamente en el dispositivo.

**v14.1 no cambia el JSON privado ni el paquete privado de imágenes IA**, por lo que si ya importaste `RAIV_datos_privados_v12.json`, no necesitas volver a importarlo.

## Cambios de v14.1

- La imagen opcional de una Carta de IA aparece ahora debajo de su texto y sus botones, de modo que la información funcional permanece siempre en primer plano.
- Añade soporte opcional para un paquete privado de **56 imágenes de Cartas IA**.
- Las imágenes se importan desde `RAIV_imagenes_IA_v1.zip` en **Datos y mantenimiento → Imágenes de cartas IA**.
- Se guardan en **IndexedDB**, separado del JSON privado y del guardado de campaña.
- El ZIP se importa una sola vez por dispositivo y la consulta funciona sin conexión.
- Las Cartas IA activas muestran un botón **Ver carta / Ocultar carta** cuando las imágenes están instaladas.
- Las imágenes sólo se cargan cuando se solicita ver una carta, evitando cargar las 56 a la vez.
- El paquete completo ocupa aproximadamente **3,8 MB** y cada imagen mide 538 × 815 px en WebP.
- Mantiene todas las funciones y mejoras de v13, incluidas Equilibrada 16/6/3 y dificultad Personalizada.

## Actualización desde v13
1. Sustituye los archivos públicos del repositorio por los de `RAIV_v14_1_publica.zip`.
2. No vuelvas a importar el JSON privado si v12 ya está cargado.
3. En cada iPad/navegador donde quieras ver las cartas, abre **Datos y mantenimiento** e importa una vez `RAIV_imagenes_IA_v1.zip`.

El ZIP de imágenes es privado y **no debe subirse al repositorio público**.
