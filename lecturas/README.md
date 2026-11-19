# Plan de lecturas · Baldwin y Schwab

Plan de 5 días para leer 6 capítulos y escribir el trabajo individual (entrega: 2 de diciembre de 2026).

- Baldwin, *La convulsión globótica*: caps. 6, 7 y 10
- Schwab, *La cuarta revolución industrial*: caps. 1, 2 y 3

## Qué tiene

- Páginas exactas del PDF por día (19 al 23 de noviembre) y marcador de "voy en la página"
- Temporizador de bloques de 25 min + 5 min de descanso
- Anotaciones por capítulo: ideas clave, conclusión, opinión y citas APA
- Plan de escritura del 24 de noviembre al 1 de diciembre
- Copiar o descargar todas las notas en .txt
- Lector integrado: botón "Leer aquí" que muestra solo las páginas del día. El PDF se carga desde el dispositivo una sola vez y se guarda en el navegador (IndexedDB); los libros no se suben al repositorio porque son públicos y tienen derechos de autor.

- Audiolibro gratis: botón "Escuchar desde esta página" con voz mexicana de Piper (mujer o hombre) que corre en el propio celular (onnxruntime-web + `piper.js`). Reproducción sin cortes (Web Audio, frases generadas por adelantado), velocidad de 0.75× a 2× sin cambiar el tono, limpieza del texto (comillas, guiones, abreviaturas, siglos en números romanos), frase anterior/siguiente, controles en la pantalla de bloqueo, recuerda dónde te quedaste y salta las notas al final de cada capítulo de Baldwin. La voz (~60 MB) se descarga una vez y queda en caché.

## Dónde se guardan las notas

Siempre en el navegador (localStorage). Si entras con tu cuenta de la Bitácora, también se guardan en Supabase (tabla `notas_lectura`, solo visible para tu usuario) y se sincronizan entre dispositivos.
