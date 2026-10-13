# Esoteric Ebb — Traducción al Español (Beta v1.3+)

> [!NOTE]
> **Compatibilidad:** Octubre de 2026 — Diseñado y testeado para la rama beta oficial de localización (**v1.3+**) de *Esoteric Ebb*.

Traducción comunitaria al castellano para el RPG de investigación y fantasía noir **Esoteric Ebb**, adaptada a la arquitectura nativa de localización introducida por el desarrollador en Steam.

---

## Agradecimientos y Origen del Proyecto

* **Traducción original (~95% del contenido):** La inmensa mayoría del texto base de esta localización fue traducida con gran dedicación por **Jordison**. Si te gusta la traducción, pásate por su guía comunitaria y dale apoyo:  
  👉 [Guía de traducción de Jordison en Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3682011521).
* **Contenido nuevo v1.3 y adaptación técnica:** Las novedades añadidas en la versión 1.3 (modos de dificultad, opciones de accesibilidad, nuevos hechizos, glosario enciclopédico de *lore* y más de 2.800 líneas de diálogo adicionales) fueron traducidas con asistencia de IA procurando preservar al máximo el tono peninsular, el humor seco y el estilo canalla establecido por Jordison.

---

## Nota Personal del Autor

* **Sin spoilers:** Personalmente **no he jugado al juego todavía**. No quería arruinarme la experiencia haciéndome *spoilers* al traducir línea a línea a mano, por lo que usé herramientas automáticas para completar las partes que faltaban de la nueva versión.
* **Mejoras progresivas:** A medida que vaya jugando la aventura, iré corrigiendo y puliendo a mano cualquier diálogo, errata o incoherencia que me vaya encontrando.
* **Sin compromiso de mantenimiento futuro:** Mi intención **no es mantener activamente este repositorio a largo plazo** ni actuar como equipo de soporte. He preparado esta traducción principalmente para mí mismo, para poder disfrutar del juego más relajadamente en mi idioma, y la comparto abiertamente con la comunidad para que cualquiera pueda aprovecharla, bifurcarla (*fork*), corregirla o redistribuirla como mejor le parezca.

---

## Instrucciones de Instalación

La beta 1.3 de *Esoteric Ebb* incluye soporte nativo para idiomas, por lo que **no necesitas ningún modloader (ni BepInEx, ni MelonLoader)** ni instalar DLLs externas.

### Paso 1: Descargar
Descarga la carpeta [`Spanish/`](./Spanish) de este repositorio (o descarga el archivo `.zip` desde el botón verde **Code > Download ZIP** de GitHub).

### Paso 2: Copiar al directorio del juego
1. En tu biblioteca de Steam, haz clic derecho sobre **Esoteric Ebb** > **Administrar** > **Ver archivos locales**.
2. Navega a la siguiente ruta dentro de la carpeta del juego:
   ```text
   Esoteric Ebb_Data/StreamingAssets/Localization/
   ```
3. Pega la carpeta `Spanish` dentro de `Localization/`. Debe quedar así:
   ```text
   Esoteric Ebb_Data/StreamingAssets/Localization/Spanish/
   ├── Dialogs.csv
   ├── EntityInfo.csv
   ├── Feats.csv
   ├── Glossary.csv
   ├── ItemTexts.csv
   ├── MiscTexts.csv
   ├── NPCInfo.csv
   ├── Popups.csv
   ├── QuestPoints.csv
   ├── SheetInfo.csv
   ├── SpellTexts.csv
   └── UIElements.csv
   ```

### Paso 3: Activar en el juego
1. Inicia el juego desde Steam.
2. Ve a **Opciones > Idioma** y selecciona **Español**.
3. **Atajos útiles dentro del juego:**
   * Pulsa <kbd>V</kbd> o <kbd>B</kbd> para alternar rápidamente entre idiomas.
   * Pulsa <kbd>Ctrl</kbd> + <kbd>R</kbd> en cualquier momento para **recargar los textos en tiempo real** sin reiniciar la partida si editas algún archivo CSV.

---

## Cobertura de la Traducción

* **Diálogos:** 100% (76.409 líneas traducidas).
* **Interfaz y Menús:** 100% (315 opciones y pantallas).
* **Glosario y Lore:** 100% (1.490 términos y definiciones).
* **Objetos, Dotes, Hechizos y Misiones:** 100% traducidos.
* **Control de Calidad (QA):** Todas las etiquetas TextMeshPro (`<i>`, `<b>`, `<shake>`, `<wiggle>`, `<color>`) y tokens de sustitución (`{0}`, `{1}`) están verificados al 100%.

---

## Licencia y Propiedad Intelectual

* El texto de esta traducción se publica bajo licencia libre **[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](./LICENSE)**. Eres libre de compartir, modificar y redistribuir el material siempre que atribuyas la autoría y mantengas la misma licencia libre.
* **Propiedad intelectual:** *Esoteric Ebb* es propiedad exclusiva de **Christoffer Bodegård**. Esta localización es un proyecto no oficial sin fines de lucro creado de acuerdo con la [publicación del desarrollador en Steam animando a la comunidad a crear sus propias traducciones](https://store.steampowered.com/news/app/2057760/view/667250959956574521?l=spanish).
