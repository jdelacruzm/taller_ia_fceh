# Ejercicios con skills en el navegador

Taller *IA generativa en la educación universitaria*, FCEH-UAT.

## Qué hay aquí

- `skills/ensayo-con-fuentes.zip`: la skill que usarás, en español y con APA 7.
- `skills/grounded-research.zip`: la skill original de GitHub, en inglés.
- `skills/ensayo-con-fuentes/SKILL.md`: ábrelo y léelo antes de subirlo.
- `skills/slidesage.zip`: SlideSage (github.com/vedraut/slidesage, MIT), lista para subir. Ejercicio 2.
- `escudo-uat.png`: el logo para las diapositivas del Ejercicio 2.
- `skills/plantilla/` y `skills/ficha-de-lectura/`: para escribir tu propia skill.

## Ejercicio 1, guiado (50 min): ensayo con fuentes

1. Descarga la lectura del taller: <https://doi.org/10.24844/EM3701.09>. En casa, usa dos o tres tuyas en PDF.
2. En claude.ai: Ajustes → Capacidades → activa "Ejecutar código en la nube".
3. Personalización → Skills → Añadir → Subir Skill → `ensayo-con-fuentes.zip`.
4. Nuevo chat, adjunta las lecturas y escribe:
   `/ensayo-con-fuentes Con las lecturas adjuntas, escribe un ensayo de una cuartilla sobre <tu tema>.`
5. Verifica al menos tres citas en el PDF: que existan y que la página impresa coincida.

En ChatGPT: Complementos → Habilidades → Añadir → Subir; después usa el modo **Work**
(no Chat) y llama la skill con `/ensa`.

Guía completa con capturas: `03_Ejercicio_Ensayo_Skill_Guia.pdf`.

## Ejercicio 2, por tu cuenta (60 min): presentación con SlideSage

1. Personalización → Skills → Añadir → Subir Skill → `skills/slidesage.zip`.
2. Nuevo chat, adjunta tus lecturas y `escudo-uat.png`, y escribe:
   `Usa la skill slidesage (no Slides). Con las lecturas adjuntas, haz una presentación de 8 a 10
   diapositivas para <tu grupo> sobre <tu tema>. Modo educativo, estilo corporate-bright, con el
   escudo adjunto como logo. Cada idea con su cita y página de la lectura. Entrega el .pptx y también un PDF.`
3. Revisa en el PDF al menos tres páginas citadas.

Guía completa con capturas: `04_Ejercicio_Presentacion_Skill_Guia.pdf`.

## Créditos y licencia

SlideSage es de Ved Raut (<https://github.com/vedraut/slidesage>), licencia MIT; el ZIP trae sus archivos sin cambios, solo sin la carpeta `.github` ni `package-lock.json`.

La skill original es *grounded-research* de The GEO Lab
(<https://github.com/arturseo-geo/grounded-research-skill>), licencia MIT.
`ensayo-con-fuentes` es una adaptación para este taller y conserva la misma licencia;
el aviso está en `skills/ensayo-con-fuentes/LICENSE`.
