# Baqueta: práctica de batería con Guitar Pro

App web para practicar batería electrónica con partituras de Guitar Pro. Combina una pista de notas estilo Guitar Hero, la partitura real con colores por instrumento y la banda del archivo sonando de fondo. Viene configurada para la **Medeli DD508DX**.

## Abrirla en la tablet

1. En este repositorio: **Settings → Pages → Branch: `main` / `(root)` → Save**.
2. Al minuto queda en **https://diegodevillaalegre.github.io/bateria/**.
3. Ábrela en **Chrome** (Android) o Chrome/Edge (Windows). Safari en iPad no soporta MIDI web.
4. Conecta la Medeli por USB (en Android, con cable OTG) y toca **Conectar batería**.
5. Opcional: menú de Chrome → **Agregar a pantalla principal**, para abrirla como app a pantalla completa.

## Sumar canciones

- **Para todos tus equipos:** sube archivos `.gp`, `.gp5`, `.gp4`, `.gp3`, `.gpx` o `.mid` a la carpeta [`songs/`](songs) (en GitHub: *Add file → Upload files*). Aparecen solos en “Canciones para practicar”.
- **Solo en ese equipo:** abre el archivo desde la app con **Abrir archivo**. Queda guardado en “Tus canciones” y no hay que volver a cargarlo.

El archivo necesita una pista de batería. Si el repositorio es público, en `songs/` sube solo material propio o con permiso. Las tablaturas de canciones comerciales ábrelas desde el equipo; quedan guardadas igual.

## Medeli DD508DX

Es el mapeo por defecto (también en [`config/medeli-dd508dx.json`](config/medeli-dd508dx.json)):

| Pad | Nota MIDI |
|---|---|
| Bombo | 36 |
| Caja | 38 (aro: 37 / 40) |
| Hi-hat cerrado / abierto / pie | 42 / 46 / 44 |
| Tom 1 / Tom 2 / Tom de piso | 48 / 45 / 43 |
| Crash | 49 |
| Ride | 51 (campana 53) |

Si un pad no coincide: **Kit y calibración → Aprender** en esa fila y golpea el pad. **Restaurar** vuelve a este mapeo.

## Cómo practicar

- **Tocar:** puntaje, rachas y medidor de adelantado/atrasado.
- **Espera:** la canción se detiene hasta que tocas la nota correcta, como en Synthesia.
- **Demo:** mira y escucha la batería sin calificar.
- Velocidad de 25% a 150%, **Repetir sección** o tramo **A-B**, y subida automática de velocidad al lograr 90%.
- **Instrumentos activos:** solo manos, solo pies, o bombo, caja y hi-hat.
- **Doble golpe de bombo** para empezar sin soltar las baquetas.
- Calibra la latencia una vez en **Kit y calibración**.

Teclado (sin batería): `S` crash, `D` hi-hat, `F` caja, `J` tom 1, `K` tom 2, `L` tom de piso, `Ñ` ride, `A` hi-hat con pie, `espacio` bombo, `Enter` reproducir o pausar.

## Canciones incluidas

Cuatro composiciones originales para esta app, con bajo y guitarra o piano: *Shuffle en La* (12/8, prepara “The Jack”), *Rock en Mi*, *Funk en Re menor* (ghost notes) y *Balada en 6/8*.

## Créditos

Lectura, partitura y reproducción con [alphaTab](https://alphatab.net) 1.8.4 (MPL-2.0), fuente musical Bravura (SIL OFL) y banco de sonidos Sonivox incluidos en alphaTab. Tipografías Atkinson Hyperlegible y Big Shoulders Display (Google Fonts).
