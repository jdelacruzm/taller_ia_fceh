# Pruebas (9 de noviembre de 2026)

Con estas pruebas se escribieron las guías. Navegador Chrome; cuentas de pago (Claude Max, ChatGPT Plus).
Falta repetirlas con una cuenta gratuita.

**Lectura usada:** Garcés Prettel, M. (2025). *Guía para el uso de IA generativa en educación e
investigación. Una reseña crítica.* Educación Matemática, 37(1), 241-244.
<https://doi.org/10.24844/EM3701.09>. No se incluye el PDF porque no declara licencia de reutilización.

| Prueba | Resultado |
|---|---|
| *grounded-research* (original, inglés) en Claude | Aplicó la skill: citas textuales con página, tabla de confianza, retractaciones; ensayo en Word. |
| *grounded-research* en ChatGPT, modo Chat | Buen ensayo, pero sin citas textuales ni páginas: no aplicó la skill. |
| *ensayo-con-fuentes* en Claude | Ensayo de unas 440 palabras y archivo de verificación, ambos en Word, en unos 3 min. |
| *ensayo-con-fuentes* en ChatGPT, modo Chat | No aplicó la skill aunque se le nombró. |
| *ensayo-con-fuentes* en ChatGPT, modo **Work** (`/ensa`) | Aplicó la skill en 1 min 37 s: citas extraídas, ensayo, tabla de verificación y documento. |
| *SlideSage* en Claude, con el escudo | 10 diapositivas en PPTX y PDF, en unos 3 min, cada idea con su página. |

**Verificación:** diez citas textuales de Claude y ChatGPT revisadas a mano contra el PDF; las diez
existen y están en la página que dicen (241 a 244).

**Hallazgos que van en las guías:** en ChatGPT las skills solo funcionan en modo *Work*; en Claude el
menú `/` muestra `slidesage` junto a *Slides* (el modo propio de Claude), por eso la petición dice
"usa la skill slidesage (no Slides)"; Claude pone como autor del archivo el nombre que tenga en la
memoria de la cuenta.

**Peticiones usadas**

```
/ensayo-con-fuentes Con la lectura adjunta, escribe un ensayo de una cuartilla sobre las
fortalezas y los pendientes de la guía de la UNESCO para usar IA generativa en educación.

Usa la skill slidesage (no Slides). Con la lectura adjunta, haz una presentación de 8 a 10
diapositivas para una clase de licenciatura en Educación sobre las fortalezas y los pendientes
de la guía de la UNESCO. Modo educativo, estilo corporate-bright, con el escudo adjunto como logo.
Cada idea con su cita y página de la lectura. Entrega el .pptx y también un PDF.
```

`capturas/`: las capturas de esas pruebas que aparecen en las presentaciones y guías.
