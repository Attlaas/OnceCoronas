# Once Coronas en itch.io: todo para publicar la demo 7.5.1

## 1. Archivos que vas a subir

| Archivo | Para qué | Casilla en itch |
|---|---|---|
| `OnceCoronas-navegador-7.5.1.zip` | Jugar en el navegador | marcar **«This file will be played in the browser»** |
| `OnceCoronas-Windows-7.5.1.zip` | Descarga para Windows (.exe) | marcar el icono de **Windows** |
| `portada-630x500.png` | Imagen de portada (Cover image) | — |
| `captura-1.png` … `captura-N.png` | Capturas (Screenshots) | — |

La versión de navegador lleva dentro three.js y las fuentes: no depende de ningún servidor externo.

## 2. Pasos en itch.io (unos 10 minutos)

1. Entra en https://itch.io y crea una cuenta (o inicia sesión). En **Settings → Payouts** configura cómo cobrar (PayPal o Stripe); si no, itch no te deja poner precio.
2. Arriba a la derecha: flecha junto a tu nombre → **Upload new project**.
3. **Title:** `Once Coronas — La guerra por Kaedra`
4. **Project URL:** `oncecoronas` (quedará `https://TUUSUARIO.itch.io/oncecoronas`).
5. **Short description or tagline:** copia el «Lema» de abajo.
6. **Classification:** Games. **Kind of project:** HTML.
7. **Release status:** *In development* (es una beta).
8. **Pricing:** *Paid* → **$1.00** o **1,00 €** (moneda en tu cuenta). Marca *Allow people to pay more* si quieres propinas.
   - Opcional: activa una **demo** gratis más adelante si quieres más reportes.
9. **Uploads:** sube los dos zip y marca las casillas de la tabla de arriba.
10. **Embed options** (aparece al marcar el zip de navegador):
    - *Viewport dimensions:* **1280 × 720**
    - Marca **Mobile friendly: NO**, **Automatically start on page load: NO** (que pulsen «Run game»; así no se pone a cargar el 3D sin querer), **Fullscreen button: SÍ**, **Enable scrollbars: NO**.
    - *SharedArrayBuffer support:* no hace falta.
11. **Details → Description:** pega la descripción (español arriba, inglés debajo).
12. **Genre:** Strategy. **Tags:** los de la lista de abajo (máximo 10).
13. **App store links / Custom noun:** déjalo vacío.
14. **Download & install instructions:** pega el texto de «Instrucciones de Windows».
15. **Community:** *Comments* (para la página) y, si quieres un sitio ordenado para fallos, *Discussion board*.
16. **Visibility & access:** primero **Draft**, pulsa **Save & view page**, comprueba que todo se ve bien y que el juego arranca, y entonces cámbialo a **Public**.
17. **Cover image:** `portada-630x500.png`. **Screenshots:** las capturas.
18. **Theme** (en la página, «Edit theme»): fondo `#070a10`, texto `#e9edf5`, enlaces `#e8c26a`, botones `#e8c26a`. Encaja con el estilo del juego.

Cuando esté publicada, pásame el enlace de la página.

## 3. Reportes de los jugadores

Ya está montado, no tienes que crear nada. El botón «⚑ Reportar fallo» del juego (menú principal y pausa) abre
https://once-coronas-reportes-5ab52269.base44.app/reportar.html con los datos técnicos ya rellenados.
Los reportes se guardan en tu app de Base44 «Once Coronas Reportes» (solo tú y yo los vemos).

## 4. Textos de la página

### Título
Once Coronas — La guerra por Kaedra

### Lema (máx. 120 caracteres)
**ES:** Estrategia en tiempo real en 3D: once facciones, guerra galáctica y planetas que conquistas palmo a palmo.
**EN:** Real-time 3D strategy: eleven factions, galactic war and planets you conquer inch by inch.

### Descripción (español)

**BETA PÚBLICA 7.5.1.** Estás comprando acceso anticipado: el juego está en pleno desarrollo y tus reportes deciden qué se arregla y mejora primero. Las actualizaciones son gratis para quien lo compre.

Once especies. Once líderes. Una sola galaxia en guerra.

**Once Coronas** es un juego de estrategia en tiempo real en 3D en el que diriges una facción desde el mapa galáctico hasta la última trinchera de cada planeta. Acerca la cámara a un mundo y bajas sin cortes a su superficie: un campo de batalla completo y persistente donde levantas bases, extraes recursos, construyes defensas planetarias y puertos espaciales para embarcar a tus tropas y llevarlas al siguiente frente.

**Qué hay en esta beta**
- **Guerra galáctica:** galaxias enteras, salto gravitacional a cualquier punto para interceptar flotas, escudos planetarios y daño por subsistemas (motores, armas, críticos) con retirada automática.
- **Once facciones únicas**, cada una con su recurso, su economía, sus tropas y su líder: de la Legión Solar y su bombardeo orbital al Sindicato Sombra invisible o la Colmena Sintética que se repara sola.
- **La Progenie Parásita**: empieza escondida en un planeta enemigo e infecta los mundos con biomasa que se extiende; sus estructuras y criaturas son biomecánicas.
- **Ciudades vivas** que crecen solas, comercian y quedan en ruinas tras la guerra.
- **Colocación libre** de estructuras y bases donde quieras.
- **Gráficos de nueva generación:** sombras suaves, luz volumétrica, iluminación cinematográfica y un preajuste «Definitiva» pensado para gráficas RTX.
- Totalmente en **español** (la interfaz aún no está traducida al inglés).

**Cómo jugar**
- **Navegador:** pulsa «Run game». Mejor en Chrome o Edge, en ordenador y con gráfica dedicada.
- **Windows:** descarga el zip, descomprímelo y abre `OnceCoronas.exe`. No necesita instalación y **se actualiza solo** cuando sale una versión nueva.
- Si va lento, baja la calidad en *Ajustes → Gráficos*.

**Reporta fallos y propón mejoras**
Esta beta existe para eso. Si algo falla, va lento o se te ocurre algo, cuéntalo con el botón «⚑ Reportar fallo» del juego o en https://once-coronas-reportes-5ab52269.base44.app/reportar.html. Cuanto más detalle (qué hacías, qué facción, versión, capturas), antes se arregla. Cada actualización incluye una lista de lo que se ha corregido gracias a vosotros.

**Requisitos recomendados:** Windows 10/11 de 64 bits o navegador moderno con WebGL 2, 8 GB de RAM, gráfica dedicada.

---

### Description (English)

**PUBLIC BETA 7.5.1.** You are buying early access: the game is in active development and your reports decide what gets fixed and improved first. Future updates are free for buyers.

Eleven species. Eleven leaders. One galaxy at war.

**Once Coronas** is a real-time 3D strategy game where you lead a faction from the galactic map down to the last trench on every planet. Zoom into a world and you descend seamlessly to its surface: a full, persistent battlefield where you build bases, mine resources, raise planetary defences and spaceports to ship your troops to the next front.

**In this beta**
- **Galactic war:** whole galaxies, gravity jumps to any point to intercept fleets, planetary shields and subsystem damage (engines, weapons, critical) with automatic retreat.
- **Eleven unique factions**, each with its own resource, economy, troops and leader.
- **The Parasite Brood** starts hidden on an enemy planet and spreads creeping biomass across worlds, with biomechanical structures and creatures.
- **Living cities** that grow, trade on their own and fall to ruins in war.
- **Free placement** of structures and bases.
- **Next-gen visuals:** soft shadows, volumetric light, cinematic lighting and a «Definitiva» preset for RTX cards.
- **Language: Spanish only for now.** English UI is planned.

**How to play:** click «Run game» (Chrome/Edge on desktop recommended), or download the Windows zip, unzip it and run `OnceCoronas.exe` (no install, auto-updates).

**Report bugs and suggest features** with the in-game «⚑ Reportar fallo» button or at https://once-coronas-reportes-5ab52269.base44.app/reportar.html. Every update lists what was fixed thanks to you.

### Etiquetas (tags, máximo 10)
`strategy`, `rts`, `real-time-strategy`, `3d`, `space`, `sci-fi`, `galaxy`, `base-building`, `aliens`, `singleplayer`

Otros campos: **Genre:** Strategy · **Made with:** Three.js · **Inputs:** Keyboard, Mouse · **Languages:** Spanish · **Average session:** About an hour · **Accessibility:** —

### Instrucciones de Windows (Download & install instructions)
Descomprime la carpeta donde quieras y abre `OnceCoronas.exe`. No necesita instalación. La primera vez Windows SmartScreen puede avisar de que es una aplicación desconocida (el ejecutable no está firmado): pulsa «Más información» → «Ejecutar de todas formas». El juego se actualiza solo al arrancar.

*Unzip anywhere and run `OnceCoronas.exe`. If SmartScreen warns you, click «More info» → «Run anyway». The game updates itself on launch.*
