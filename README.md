# Taller *IA generativa en la educación universitaria* (FCEH-UAT)

Facultad de Ciencias de la Educación y Humanidades, Universidad Autónoma de Tamaulipas.
El bloque práctico (2 h 30 min) usa solo el navegador: no se instala nada.

| Hora | Bloque |
|---|---|
| 0:00 a 0:15 | Qué es una skill y cómo se personaliza la IA |
| 0:15 a 1:05 | **Ejercicio 1, guiado:** skill *ensayo-con-fuentes*, ensayo en Word con citas verificables |
| 1:05 a 1:15 | Receso |
| 1:15 a 2:15 | **Ejercicio 2, por tu cuenta:** skill *SlideSage* de GitHub, presentación en PowerPoint y PDF |
| 2:15 a 2:30 | Cierre y ticket de salida |

## Antes de empezar (5 minutos)

1. Descarga y descomprime [`participantes/ejercicio-ensayo.zip`](participantes/ejercicio-ensayo.zip).
2. Entra a <https://claude.ai> con tu correo personal (la cuenta gratuita sirve).
3. Ve a **Ajustes → Capacidades** y activa **Ejecutar código en la nube**. Sin esto no funcionan las skills.

## Ejercicio 1, guiado: ensayo con fuentes verificables

1. Descarga la lectura del taller: <https://doi.org/10.24844/EM3701.09> (botón de PDF).
2. En Claude: **Personalización → Skills → + Añadir → Subir Skill** y elige
   `skills/ensayo-con-fuentes.zip`. Da clic en **Subir**.
3. Abre un **chat nuevo** y adjunta el PDF de la lectura con el botón **+**.
4. Escribe `/ensayo`, elige **ensayo-con-fuentes** en el menú y completa la petición:

   ```
   /ensayo-con-fuentes Con la lectura adjunta, escribe un ensayo de una cuartilla sobre
   las fortalezas y los pendientes de la guía de la UNESCO para usar IA generativa en educación.
   ```

5. Espera de 2 a 4 minutos. Comprueba que en el panel derecho diga **Skills: ensayo-con-fuentes**.
6. Descarga los dos archivos de Word: el **ensayo** y el de **verificación**.
7. **Verifica tres citas:** abre el PDF, busca cada cita con **Ctrl+F** y confirma que la página
   impresa coincide con la del ensayo.

¿Usas ChatGPT? **Complementos → Habilidades → Añadir → Subir desde tu ordenador**; luego, arriba,
cambia de **Chat** a **Work** y llama la skill con `/ensa`. En modo Chat la ignora.

Guía completa con capturas: [`03_Ejercicio_Ensayo_Skill_Guia.pdf`](participantes/03_Ejercicio_Ensayo_Skill_Guia.pdf).

## Ejercicio 2, por tu cuenta: presentación con SlideSage

1. Ten listas **dos o tres lecturas tuyas** en PDF (con texto seleccionable) y el archivo
   `escudo-uat.png` de la carpeta del taller.
2. En Claude: **Personalización → Skills → + Añadir → Subir Skill** y elige `skills/slidesage.zip`.
3. Abre un **chat nuevo** y adjunta tus lecturas **y** el escudo con el botón **+**.
4. Copia esta petición y cambia lo que está entre corchetes:

   ```
   Usa la skill slidesage (no Slides). Con las lecturas adjuntas, haz una presentación de 8 a 10
   diapositivas para [tu grupo o materia] sobre [tu tema]. Modo educativo, estilo corporate-bright,
   con el escudo adjunto como logo. Cada idea con su cita y página de la lectura.
   Entrega el .pptx y también un PDF.
   ```

5. **Ojo:** si escribes `/slides` no des Enter, porque elige *Slides*, el modo propio de Claude, y no la skill.
   Si debajo de la caja de texto se enciende un ícono de presentación, apágalo.
6. Espera unos 3 minutos y descarga el **.pptx** y el **PDF** con **Descargar todo**.
7. **Revisa tres viñetas:** abre tus lecturas en la página citada y confirma que dicen eso.
   En PowerPoint, revisa en **Archivo → Información** que el autor seas tú.

Guía completa con capturas: [`04_Ejercicio_Presentacion_Skill_Guia.pdf`](participantes/04_Ejercicio_Presentacion_Skill_Guia.pdf).

## Ticket de salida (al final)

Media cuartilla con: una cita que verificaste (de cualquiera de los dos ejercicios) y su página,
una regla que agregarías a una skill para tu materia, y la declaración de uso de IA.

## Contenido

- [`presentacionIA.pptx`](presentacionIA.pptx): presentación general del taller.
- [`presentaciones/`](presentaciones/): las presentaciones de los dos ejercicios, en PDF y PowerPoint.
- [`participantes/`](participantes/): lo que necesitan los participantes. Descarga directa:
  [`ejercicio-ensayo.zip`](participantes/ejercicio-ensayo.zip) (skills listas para subir, escudo, plantilla y guías).
- [`pruebas/`](pruebas/): registro de las pruebas con las que se escribieron las guías y sus capturas.
- [`PropuestaTallerIA_v3.docx`](PropuestaTallerIA_v3.docx): propuesta académica.

## Créditos

Skills de terceros, con licencia MIT: *grounded-research* de The GEO Lab
(<https://github.com/arturseo-geo/grounded-research-skill>) y *SlideSage* de Ved Raut
(<https://github.com/vedraut/slidesage>). *ensayo-con-fuentes* es una adaptación de la primera.
