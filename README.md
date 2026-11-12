# Drafter

Coach de draft para League of Legends en una ventana para la segunda pantalla. Sigue tu selección de campeones en
tiempo real y te dice qué elegir (priorizando la línea inferior), qué banear, cómo va cada enfrentamiento, qué build
hacer y cómo jugar los primeros 15 minutos. La **build se adapta a cada partida**: contra un equipo que se cura
mucho, tanques, casi todo daño físico o mágico, asesinos o supresiones, mete en su puesto el objeto que encaja con tu
campeón (Recordatorio letal un tirador, Malla de espinas un tanque, Morellonomicón un mago…), elige las botas de esa
partida para tu línea y te dice por qué. Las estadísticas son reales (OP.GG, parche actual) y tiene un Coach IA
opcional con la IA que prefieras: analiza tu draft, **contesta en un chat** lo que le preguntes de League (runas,
enfrentamientos, builds, cómo jugar algo) con los datos del parche actual, y hace la **review de tu perfil** con
todas tus partidas: qué haces bien, qué te está costando partidas y cómo mejorar. Si la IA está saturada (el típico
error 503 de Gemini) o tarda en empezar a contestar, responde al momento otro modelo de la misma IA (nunca uno más
caro) y te dice cuál.

En **Perfil** tienes tu **historial de partidas**: al abrir una ves **por qué ganaste o perdiste**, sus **momentos
decisivos** con su porqué (cada pelea con los retratos de quién mató a quién y un minimapa de dónde pasó), un **mapa
de la partida** ampliable, con solo lo tuyo o con todo y una **repetición** con dónde estaba cada uno minuto a minuto, la diferencia de oro minuto a minuto, el marcador de los diez jugadores
(con sus runas, objetos y los objetivos de cada equipo en iconos) y tu fase de líneas (y, con el Coach IA, el coach
te la explica). Puedes **buscar a cualquier invocador** por su Riot ID y ver su
perfil (rango, cómo viene, sus campeones y sus partidas) y, **desde la pantalla de carga**, el perfil de los cinco
rivales y de tu equipo: su rango y su win rate, cuánto han jugado a su campeón, cómo juegan (KDA, farmeo, primera
sangre), cómo vienen (también hoy), quiénes juegan juntos y qué hacer contra cada uno.

Y la **ventanita**, como la de Porofessor o Blitz: una ventana pequeña que se abre sola en cada selección de
campeones (en tu segunda pantalla) con lo útil de cada momento. Qué banear y qué elegir, tu build y tu plan; en la
pantalla de carga, los diez jugadores con su rango y cómo vienen; y durante la partida, el marcador con el **oro en
objetos** de cada equipo, **cuándo sale cada objetivo**, tus números frente a tu rival y **tu siguiente compra**.
En **ARAM y ARAM: Caos** enseña solo lo necesario: tu build de ARAM y, en Caos, tus mejores aumentos; y al elegir
aumento, pone bajo cada carta **su tier con tu campeón** (S, A, B…) encima del juego (con el juego en modo sin bordes
o ventana). Y al acabar cada partida, un **resumen** contigo en grande: tu campeón, tu KDA, tu daño, curación,
escudos, oro, medallas y los diez jugadores.

Y el **companion**: Federico, un pequeño inventor que vive en tu pantalla (o, si lo prefieres, Xayah en versión
chibi; cada uno con su propia voz de balbuceo, grave o aguda). Haz clic en él y pídele con tus
palabras «búscame soloq en 5 minutos, pickea akali mid y banea fizz»: te pregunta lo necesario (tu segunda línea, a
quién pickear si te banean o te toca autofill, qué hacer si eres first pick…), lo recuerda para la próxima vez, y
a su hora busca la partida, la acepta, banea y pickea por ti, siempre con unos segundos para que lo cambies tú. Camina
por tu pantalla (o solo por el cliente, moviéndose con él), solo aparece con League abierto y tiene sus caras y sus
sonidos. En la selección de campeones comenta de vez en cuando los picks de los dos equipos (cada campeón tiene su
frase), y durante la partida solo se asoma por un lado de la pantalla para avisarte de lo que te puedes perder: la
primera sangre, los objetivos que salen o se cogen, las torres de tu línea, tu rival de línea muerto, el oro en
objetos con tu rival, tu farm, puntos de habilidad sin usar… Solo usa lo que el propio juego enseña (nada de
enfriamientos ni posiciones rivales) y nunca toca el ratón ni el teclado. Se activa con el botón del robot de la
barra de título.

¿Demasiada información? Elige el **Modo simple** (la app lo pregunta la primera vez que la abres, y se cambia cuando
quieras en *Ajustes*): cada pestaña enseña solo lo imprescindible para entender el draft y tu línea.

**Also in English:** *Ajustes → Idioma · Language* pone toda la app, y las respuestas del Coach IA, en inglés.

## Descargar

**[⬇ Descargar el instalador para Windows](https://github.com/intoher/coach-de-draft-lol/releases/latest/download/Drafter-Setup.exe)** (Windows 10 u 11 de 64 bits, unos 89 MB)

1. Abre el instalador. Como la app no está firmada, Windows puede avisar con "Windows protegió su PC": pulsa
   **Más información** y después **Ejecutar de todas formas**. El navegador también puede preguntar si quieres
   conservar el archivo.
2. Se instala en tu carpeta de usuario, sin permisos de administrador, y deja un acceso directo en el escritorio y en
   el menú Inicio.
3. Abre el cliente de League: la app se conecta sola.

## Actualizaciones

Solo hay que instalarla una vez. Cuando sale una versión nueva, la app te avisa (nunca en cola, selección de campeones
ni partida) y mientras no la instales tienes el botón **Actualizar** arriba a la izquierda, junto a la versión: un clic
y se cierra y se vuelve a abrir sola en unos segundos, ya actualizada. Si prefieres que se
actualice sola, activa la *Actualización automática* en *Ajustes → Actualizaciones*: entonces la descarga de aquí y la
instala en silencio, sin interrumpirte.

Todas las versiones: [Releases](https://github.com/intoher/coach-de-draft-lol/releases).

## Privacidad

- Lee la selección de campeones del propio cliente de League (la API local que usan Blitz, Porofessor, U.GG…). Por
  su cuenta no automatiza nada; solo si usas el companion (desactivado de serie), hace lo que le encargues y
  confirmes: buscar partida, aceptarla, banear y pickear (Riot no tiene una API oficial para esto; úsalo bajo tu
  responsabilidad).
- Durante la selección de campeones no consulta nada de ningún jugador. Con la partida ya empezada, lee en tu
  cliente el rango, la maestría y las últimas partidas de los jugadores de la partida, como hacen las apps de partida
  en vivo; lo leído no se guarda ni se envía a ningún sitio. Se desactiva en *Ajustes*.
- Durante la partida, la ventanita lee la API de partida del propio juego (en tu PC, la misma del marcador del Tab):
  solo lo que el juego ya enseña a cualquier jugador, y nada sale de tu PC.
- En ARAM: Caos, para saber qué cartas de aumento te ofrece el juego, lee la pantalla del juego con el OCR de
  Windows (sin tocar el juego) y guarda en tu PC una captura de las primeras cartas que ve (para ajustar dónde va la
  letra); nada de eso sale de tu PC. Se desactiva en *Ajustes*.
- Los perfiles de otros invocadores y el detalle de cada partida se piden a tu propio cliente de League, nunca a
  terceros.
- Fuera de tu PC solo pide estadísticas de campeones y de aumentos a OP.GG, datos del juego a Riot (Data Dragon y notas de parche),
  las versiones nuevas a esta página y, si activas el Coach IA, lo que le pidas (el resumen del draft, tus preguntas
  del chat, el resumen de tus partidas para la review o la partida que quieres que te explique) a la IA que elijas,
  con tu propia key y sin nombres de jugadores.
- Tus partidas (campeones, resultado y tus estadísticas, sin nombres de jugadores) se guardan solo en tu PC.

## Desinstalar

Configuración de Windows → Aplicaciones → Drafter → Desinstalar.

---

Drafter no está respaldada por Riot Games y no refleja las opiniones de Riot Games ni de nadie implicado
oficialmente en producir o gestionar propiedades de Riot Games. Riot Games y todas las propiedades asociadas son
marcas comerciales o marcas registradas de Riot Games, Inc.
