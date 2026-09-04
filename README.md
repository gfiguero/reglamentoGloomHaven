# Gloomhaven — Reglamento oficial (1.ª edición, español)

> **Qué es esto.** Transcripción completa del reglamento oficial en Markdown, ordenada
> para resolver dudas durante la partida. Empieza por **Consulta rápida**, tira del
> **Índice de términos** si no sabes en qué apartado cae la duda, y baja al cuerpo del
> reglamento para el texto literal.
>
> - Los comentarios `<!-- pág. N -->` marcan la página del PDF original.
> - Los iconos del juego son dibujos en el PDF; aquí van como `[escudo]`, `[una mano]`, `[fuego]`…
> - El texto suelto de las ilustraciones está en `figuras-en-bruto.md`, fuera de aquí:
>   es material sin depurar y no debe usarse para responder reglas.

Gloomhaven es un juego cooperativo en el que los jugadores combaten monstruos y
progresan para alcanzar sus objetivos individuales. El juego está pensado para jugarse como
parte de una campaña, en la que un grupo de jugadores empleará el Libro de escenarios incluido
para encadenar una serie de aventuras y desbloquear nuevo contenido para el juego a medida que
avanzan. Sin embargo, cualquier escenario revelado también puede servir como experiencia
independiente con un alto grado de variabilidad.

Este reglamento está dividido en dos partes: la primera parte te enseñará a jugar un escenario
individual y a interactuar con los monstruos y el entorno mediante cartas de Capacidad de
personaje. La segunda te enseñará a usar el Libro de escenarios para enlazar una serie de
aventuras y crear una historia propia, hacer progresar las capacidades de tu personaje y
desbloquear nuevo contenido para enriquecer aún más tu experiencia.

## Consulta rápida

> Resumen de lo que más se pregunta en mesa. Cada punto enlaza al apartado que lo desarrolla; ante cualquier duda o caso raro, manda el apartado, no este resumen.

### Secuencia de la ronda

1. **[Selección de cartas](#selección-de-cartas):** cada jugador elige 2 cartas en secreto, o declara **descanso largo**. De las 2, una es la *carta principal* y su iniciativa es la del jugador.
2. **[Determinar la iniciativa](#determinar-la-iniciativa):** se revelan las cartas de los jugadores y 1 carta de Capacidad por cada tipo de monstruo en el tablero.
3. **[Turnos](#turno-de-los-personajes):** por orden de iniciativa, de menor a mayor.
4. **[Final de la ronda](#final-de-la-ronda):** limpieza.

### Resolución de un ataque

Se aplica **por cada enemigo objetivo por separado**, en este orden (consulta [Ataque](#ataque)):

1. **Modificadores del atacante:** cartas activas, objetos, Ataque +1 por VENENO…
2. **1 carta de Modificador de ataque** robada de su mazo — *una carta por cada objetivo*.
3. **Bonificaciones defensivas del defensor:** Escudo y similares.

Si hay varios modificadores en un mismo paso, el jugador elige el orden. Como las bonificaciones se aplican por objetivo, un mismo ataque puede infligir daño distinto a cada enemigo.

**[Ventaja y desventaja](#ventaja-y-desventaja):** con ventaja se roban 2 cartas de Modificador y se usa la mejor; en desventaja se roban 2 y se usa la peor, ignorando los Modificadores de racha. Un **ataque a distancia contra un enemigo adyacente está en desventaja**.

### Estados de un vistazo

Un estado no se acumula: o se tiene o no se tiene. Consulta [Estados](#estados).

**Negativos**

| Estado | Efecto | Se retira |
|---|---|---|
| VENENO | Los enemigos suman Ataque +1 contra la figura envenenada. | Al curarla: se retira la ficha y la curación no tiene más efecto. |
| HERIDA | Sufre 1 punto de daño al comienzo de cada uno de sus turnos. | Al curarla: se retira la ficha y la curación se aplica con normalidad. |
| INMOVILIZACIÓN | No puede usar ninguna capacidad de movimiento. | Al final de su siguiente turno. |
| DESARME | No puede usar ninguna capacidad de ataque. | Al final de su siguiente turno. |
| ATURDIMIENTO | No puede usar capacidades ni objetos; un personaje sólo puede realizar un descanso largo. | Al final de su siguiente turno. |
| CONFUSIÓN | Está en desventaja en todos sus ataques. | Al final de su siguiente turno. |
| MALDICIÓN | Añade 1 carta de MALDICIÓN a su mazo de Modificadores de ataque. | Al revelarse la carta: se retira del mazo. |

**Positivos**

| Estado | Efecto | Se retira |
|---|---|---|
| INVISIBILIDAD | Los enemigos no pueden centrarse en ella ni tomarla como objetivo. No afecta a sus aliados. | Al final de su siguiente turno. |
| FORTALECIMIENTO | Tiene ventaja en todos sus ataques. | Al final de su siguiente turno. |
| BENDICIÓN | Añade 1 carta de BENDICIÓN a su mazo de Modificadores de ataque. | Al revelarse la carta: se retira del mazo. |

### Descanso corto y largo

Requiere 2 o más cartas en la pila de descartes y **siempre cuesta perder 1 carta** (consulta [Descanso](#descanso)).

|  | Descanso corto | Descanso largo |
|---|---|---|
| Cuándo | En la limpieza, al final de la ronda | Se declara en la selección de cartas |
| Coste del turno | Ninguno | Consume el turno entero; iniciativa **99** |
| Carta perdida | Al azar | La eliges tú |
| Repetir la pérdida | Sí, sufriendo 1 daño (una vez por descanso) | — |
| Extras | — | Curación 2 (Personal) y repone los objetos gastados |

### Qué se hace al final de la ronda

Consulta [Final de la ronda](#final-de-la-ronda).

- Si se reveló un **“2x” o un “Nulo”**, se devuelven al mazo todos los descartes de ese mazo de Modificadores y se baraja.
- Si una carta de Capacidad de monstruo tenía el **símbolo de devolución**, se rebaraja el mazo de ese tipo de monstruo.
- Las **inducciones elementales** bajan un escalón: Fuerte → Menguante → Inerte.
- Las **cartas activas** agotadas van a descartes o a pérdida, según su símbolo.
- Quien pueda y quiera, hace un **descanso corto**.

### Desempates y casos dudosos

- **Empate de iniciativa entre jugadores:** decide la carta *no* principal; si sigue el empate, lo acuerdan entre ellos.
- **Empate entre jugador y monstruo:** actúa antes el jugador.
- **Empate entre dos tipos de monstruo:** lo deciden los jugadores.
- **Monstruos del mismo tipo:** primero los de élite, luego los normales, y dentro de cada grupo en orden ascendente del número de la figura (consulta [Orden de actuación](#orden-de-actuación)).
- **Acción de monstruo ambigua** (varios hexágonos o varios objetivos igual de válidos): **deciden los jugadores** (consulta [Ambigüedad](#ambigüedad)).
- **Dos cartas de Modificador igual de buenas o malas:** se usa la robada en primer lugar.

---

## Índice de términos

> Qué apartado resuelve cada duda. Incluye el término en inglés y los sinónimos de mesa.

| Si buscas… | Ve a | Recordatorio |
|---|---|---|
| acción superior, acción inferior, top, bottom | [turno de los personajes](#turno-de-los-personajes) |  |
| adyacente, adjacency | [ataque](#ataque) |  |
| agotamiento, agotado, exhausted, muerte | [agotamiento](#agotamiento) |  |
| alcance, rango, range | [ataque](#ataque) | Alcance Y: hexágonos de distancia |
| aleatoriedad reducida | [variante de juego aleatoriedad reducida](#variante-de-juego-aleatoriedad-reducida) |  |
| ambigüedad, duda, caso dudoso | [ambigüedad](#ambigüedad) | Ante la duda, deciden los jugadores |
| anales, anales de la ciudad | [anales de la ciudad](#anales-de-la-ciudad) |  |
| ataque de zona, área, AoE, hexágonos rojos | [efectos de zona](#efectos-de-zona) |  |
| ataque que hace un monstruo | [ataques de los monstruos](#ataques-de-los-monstruos) |  |
| ataque, atacar, attack | [ataque](#ataque) | **Regla general del ataque** |
| atención, foco, centrarse, focus | [atención de los monstruos](#atención-de-los-monstruos) |  |
| aturdimiento, stun, aturdido | [estados](#estados) |  |
| añadir objetivo, add target | [efectos de ataques](#efectos-de-ataques) |  |
| bendición, bless, bendecido | [estados](#estados) |  |
| campaña, campaign | [descripción de la campaña](#descripción-de-la-campaña) |  |
| carta activa, bonificación continua, de ronda | [bonificaciones activas](#bonificaciones-activas) |  |
| carta de Atributos, funda de monstruo | [cartas de atributos de monstruo](#cartas-de-atributos-de-monstruo) |  |
| carta perdida, pérdida, lost card | [turno de los personajes](#turno-de-los-personajes) |  |
| carta principal, iniciativa, initiative | [determinar la iniciativa](#determinar-la-iniciativa) |  |
| condición de victoria, objetivo del escenario | [terminar un escenario](#terminar-un-escenario) |  |
| confusión, muddle, confundido | [estados](#estados) |  |
| consumir elemento, usar elemento | [inducciones elementales](#inducciones-elementales) |  |
| cuerpo a cuerpo, melé, melee | [ataque](#ataque) | Sin valor de alcance = alcance 1 |
| curación, curar, heal | [curación](#curación) |  |
| daño, sufrir daño, damage | [daño de los personajes](#daño-de-los-personajes) |  |
| desarme, disarm, desarmado | [estados](#estados) |  |
| descanso, descansar, rest, corto, largo | [descanso](#descanso) |  |
| diseño de objeto (plano), item design | [cartas de diseño de objeto](#cartas-de-diseño-de-objeto) |  |
| donar, santuario, sanctuary | [donar al santuario](#donar-al-santuario) |  |
| elemento, elementos, inducción elemental | [inducciones elementales](#inducciones-elementales) |  |
| empujón, push, desplazar | [efectos de ataques](#efectos-de-ataques) |  |
| escudo, shield, armadura | [escudo](#escudo) |  |
| estado, estados, condición, condition | [estados](#estados) | **Lista completa de estados** |
| evento de camino, evento de ciudad, road, city event | [cartas de evento de camino y de ciudad](#cartas-de-evento-de-camino-y-de-ciudad) |  |
| experiencia, XP, puntos de experiencia | [obtención de experiencia](#obtención-de-experiencia) |  |
| fortalecimiento, strengthen, fortalecido | [estados](#estados) |  |
| fuego, hielo, aire, tierra, luz, oscuridad | [inducciones elementales](#inducciones-elementales) |  |
| herida, wound, herido | [estados](#estados) |  |
| hoja de grupo, party sheet | [hoja de grupo](#hoja-de-grupo) |  |
| inmovilización, immobilize, inmovilizado | [estados](#estados) |  |
| invisibilidad, invisible, invisibility | [estados](#estados) |  |
| invocación, invocar, summon | [invocación](#invocación) |  |
| jefe, boss | [jefes](#jefes) |  |
| logro, logros, achievement | [logros](#logros) |  |
| línea de visión, line of sight, LOS | [ataque](#ataque) |  |
| maldición, curse, maldito | [estados](#estados) |  |
| mano de cartas, límite de mano, hand size | [crear una mano de cartas](#crear-una-mano-de-cartas) |  |
| mapa, ubicación, desbloquear escenario | [mapa de campaña](#mapa-de-campaña) |  |
| mazmorra aleatoria, random dungeon | [variante de juego mazo de mazmorras aleatorias](#variante-de-juego-mazo-de-mazmorras-aleatorias) |  |
| mejorar carta, upgrade, coste de mejora | [mejorar cartas de capacidad](#mejorar-cartas-de-capacidad) |  |
| misión personal, personal quest, retiro | [cartas de misión personal](#cartas-de-misión-personal) |  |
| modificador de ataque, mazo de modificadores | [cartas de modificador de ataque](#cartas-de-modificador-de-ataque) |  |
| monstruo, monstruos, monster | [turno de los monstruos](#turno-de-los-monstruos) |  |
| movimiento de monstruo, ruta, pathing | [movimiento de los monstruos](#movimiento-de-los-monstruos) |  |
| movimiento, mover, move | [movimiento](#movimiento) | **Regla general del movimiento** |
| muerte permanente, permadeath | [variante de juego muerte permanente](#variante-de-juego-muerte-permanente) |  |
| nivel del escenario, dificultad | [nivel del escenario](#nivel-del-escenario) |  |
| nuevo personaje, crear personaje | [crear nuevos personajes](#crear-nuevos-personajes) |  |
| nulo, null, 2x, doble daño | [cartas de modificador de ataque](#cartas-de-modificador-de-ataque) |  |
| objetivo de batalla, battle goal, marcas | [cartas de objetivo de batalla](#cartas-de-objetivo-de-batalla) |  |
| objetivo X, varios objetivos, multi-target | [efectos de zona](#efectos-de-zona) | 1 carta de Modificador por objetivo |
| objeto, objetos, item, equipar | [objetos](#objetos) | Uso durante el escenario |
| obstáculo, obstacle | [tipos de piezas de terreno](#tipos-de-piezas-de-terreno) |  |
| pared, muro, wall | [ataque](#ataque) | Sólo las paredes bloquean la línea de visión |
| pasillo, corridor | [tipos de piezas de terreno](#tipos-de-piezas-de-terreno) |  |
| perforante, pierce | [efectos de ataques](#efectos-de-ataques) | Ignora escudo, no lo reduce |
| pericia, perk, pericias | [pericias adicionales](#pericias-adicionales) |  |
| preparación, montar escenario, setup | [preparación del escenario](#preparación-del-escenario) |  |
| prosperidad, prosperity | [prosperidad de gloomhaven](#prosperidad-de-gloomhaven) |  |
| puerta, door, revelar sala | [revelar una sala](#revelar-una-sala) |  |
| racha, rolling, modificador de racha | [ventaja y desventaja](#ventaja-y-desventaja) |  |
| recuperar, reponer, recover, refresh | [recuperación y reposición](#recuperación-y-reposición) |  |
| reglas especiales | [reglas especiales de los escenarios](#reglas-especiales-de-los-escenarios) |  |
| represalia, retaliate | [represalia](#represalia) |  |
| reputación, reputation, precios | [reputación](#reputación) |  |
| retirarse, retirada, retire | [anunciar la retirada de un personaje](#anunciar-la-retirada-de-un-personaje) |  |
| salto, jump, saltar | [movimiento](#movimiento) |  |
| saqueo, saquear, loot, dinero, oro | [saqueo](#saqueo) |  |
| sobre, sobres cerrados, caja cerrada | [cajas y sobres cerrados](#cajas-y-sobres-cerrados) |  |
| solitario, en solitario, información pública | [variante de juego información pública y juego en solitario](#variante-de-juego-información-pública-y-juego-en-solitario) |  |
| subir de nivel, level up | [subir de nivel](#subir-de-nivel) |  |
| terminar escenario, éxito, fracaso | [terminar un escenario](#terminar-un-escenario) |  |
| terreno impracticable, difficult terrain | [tipos de piezas de terreno](#tipos-de-piezas-de-terreno) | Cuesta 2 de movimiento |
| terreno peligroso, hazardous terrain | [tipos de piezas de terreno](#tipos-de-piezas-de-terreno) |  |
| tienda, comprar, vender, objetos disponibles | [comprar y vender objetos](#comprar-y-vender-objetos) |  |
| tirón, pull, atraer | [efectos de ataques](#efectos-de-ataques) |  |
| trampa, trap, trampas | [tipos de piezas de terreno](#tipos-de-piezas-de-terreno) |  |
| veneno, poison, envenenado | [estados](#estados) |  |
| ventaja, desventaja, advantage, disadvantage | [ventaja y desventaja](#ventaja-y-desventaja) |  |
| vuelo, volar, fly, flying | [movimiento](#movimiento) |  |
| élite, elite, normal | [orden de actuación](#orden-de-actuación) | Los de élite actúan primero |

---

## Tablas de consulta

> Reunidas aquí para no tener que calcularlas ni buscarlas por el texto.

### Experiencia necesaria para subir de nivel

| Nivel del personaje | Experiencia necesaria |
|---|---|
| 1 | 0 |
| 2 | 45 |
| 3 | 95 |
| 4 | 150 |
| 5 | 210 |
| 6 | 275 |
| 7 | 345 |
| 8 | 420 |
| 9 | 500 |

### Nivel de escenario según la dificultad

Nivel sugerido: **nivel medio del grupo ÷ 2, redondeando hacia arriba**. Se puede ajustar con la dificultad (consulta [Nivel del escenario](#nivel-del-escenario)).

| Dificultad | Modificación de nivel |
|---|---|
| Fácil | -1 |
| Normal | +0 |
| Difícil | +1 |
| Muy difícil | +2 |

| Nivel del escenario | Nivel de los monstruos | Conversión de oro | Daño de las trampas | Experiencia extra |
|---|---|---|---|---|
| 0 | 0 | 2 | 2 | 4 |
| 1 | 1 | 2 | 3 | 6 |
| 2 | 2 | 3 | 4 | 8 |
| 3 | 3 | 3 | 5 | 10 |
| 4 | 4 | 4 | 6 | 12 |
| 5 | 5 | 4 | 7 | 14 |
| 6 | 6 | 5 | 8 | 16 |
| 7 | 7 | 6 | 9 | 18 |

**En solitario o con información pública** (consulta [Variante de juego: información pública y juego en solitario](#variante-de-juego-información-pública-y-juego-en-solitario)): sube en 1 el nivel de los monstruos y el daño de las trampas, sin tocar la conversión de oro ni la experiencia extra.

| Nivel del escenario | Nivel de los monstruos | Conversión de oro | Daño de las trampas | Experiencia extra |
|---|---|---|---|---|
| 0 | 1 | 2 | 3 | 4 |
| 1 | 2 | 2 | 4 | 6 |
| 2 | 3 | 3 | 5 | 8 |
| 3 | 4 | 3 | 6 | 10 |
| 4 | 5 | 4 | 7 | 12 |
| 5 | 6 | 4 | 8 | 14 |
| 6 | 7 | 5 | 9 | 16 |

### Objetos que puede equipar un personaje

Una cabeza, un cuerpo, unas piernas, y **dos objetos de una mano O BIEN uno de dos manos**. Los objetos pequeños dependen del nivel: la mitad, redondeando hacia arriba (consulta [Cartas de Objeto](#cartas-de-objeto)).

| Nivel del personaje | Objetos pequeños |
|---|---|
| 1 | 1 |
| 2 | 1 |
| 3 | 2 |
| 4 | 2 |
| 5 | 3 |
| 6 | 3 |
| 7 | 4 |
| 8 | 4 |
| 9 | 5 |

### Costes de mejora de cartas de Capacidad

El coste total es **coste básico + recargo por nivel de carta + recargo por mejoras anteriores**, doblando el básico si la capacidad tiene objetivos múltiples (consulta [Mejorar cartas de Capacidad](#mejorar-cartas-de-capacidad)).

**Coste de mejora básico de +1**

| Mejora | Coste |
|---|---|
| Movimiento +1 | 30 o |
| Ataque +1 | 50 o |
| Alcance +1 | 30 o |
| Escudo +1 | 100 o |
| EMPUJÓN +1 | 30 o |
| TIRÓN +1 | 30 o |
| PERFORANTE +1 | 30 o |
| Represalia +1 | 100 o |
| Curación +1 | 30 o |
| Objetivo +1 | 50 o |

**Coste de mejora básico de +1 (para invocaciones)**

| Mejora | Coste |
|---|---|
| Movimiento | 100 o |
| Ataque | 100 o |
| Alcance | 50 o |
| PV | 50 o |

**Coste básico de otros efectos**

| Efecto añadido | Coste |
|---|---|
| VENENO | 75 o |
| HERIDA | 75 o |
| CONFUSIÓN | 50 o |
| INMOVILIZACIÓN | 100 o |
| DESARME | 150 o |
| MALDICIÓN | 75 o |
| FORTALECIMIENTO | 50 o |
| BENDICIÓN | 50 o |
| Salto | 50 o |
| Elemento concreto | 100 o |
| Cualquier elemento | 150 o |

**Recargo por nivel de la carta de Capacidad**

| Nivel de carta | Recargo |
|---|---|
| 1 | + 0 o |
| 2 | + 25 o |
| 3 | + 50 o |
| 4 | + 75 o |
| 5 | + 100 o |
| 6 | + 125 o |
| 7 | + 150 o |
| 8 | + 175 o |
| 9 | + 200 o |

**Recargo por cantidad de mejoras anteriores en esa acción**

| Mejoras anteriores | Recargo |
|---|---|
| 0 | + 0 o |
| 1 | + 75 o |
| 2 | + 150 o |
| 3 | + 225 o |

- **Se dobla el coste básico** para cualquier capacidad con objetivos múltiples.
- **Añadir un hexágono de ataque:** 200 o divididos por el número de hexágonos que tenga como objetivo el ataque en ese momento (redondeando hacia abajo).

### Objetos disponibles en la tienda según la prosperidad

| Prosperidad | Cartas de Objeto |
|---|---|
| 1 | 001–014 |
| 2 | 015–021 |
| 3 | 022–028 |
| 4 | 029–035 |
| 5 | 036–042 |
| 6 | 043–049 |
| 7 | 050–056 |
| 8 | 057–063 |
| 9 | 064–070 |

---

## Índice del reglamento

- [Descripción del juego](#descripción-del-juego)  <sub>pág. 4-12</sub>
  - [Tarjetas de personaje](#tarjetas-de-personaje)  <sub>pág. 6</sub>
  - [Cartas de Capacidad de personaje](#cartas-de-capacidad-de-personaje)  <sub>pág. 7</sub>
  - [Cartas de Objeto](#cartas-de-objeto)  <sub>pág. 8</sub>
  - [Cartas de Atributos de monstruo](#cartas-de-atributos-de-monstruo)  <sub>pág. 9</sub>
  - [Cartas de Capacidad de monstruo](#cartas-de-capacidad-de-monstruo)  <sub>pág. 10</sub>
  - [Cartas de Objetivo de batalla](#cartas-de-objetivo-de-batalla)  <sub>pág. 10</sub>
  - [Cartas de Modificador de ataque](#cartas-de-modificador-de-ataque)  <sub>pág. 11</sub>
- [Preparación del escenario](#preparación-del-escenario)  <sub>pág. 12-16</sub>
  - [Página de escenario](#página-de-escenario)  <sub>pág. 12-13</sub>
  - [Piezas de Terreno](#piezas-de-terreno)  <sub>pág. 14-15</sub>
  - [Nivel del escenario](#nivel-del-escenario)  <sub>pág. 15</sub>
  - [Variante de juego: información pública y juego en solitario](#variante-de-juego-información-pública-y-juego-en-solitario)  <sub>pág. 16</sub>
- [Descripción de la ronda](#descripción-de-la-ronda)  <sub>pág. 16-31</sub>
  - [Selección de cartas](#selección-de-cartas)  <sub>pág. 16-17</sub>
    - [Descanso](#descanso)  <sub>pág. 17</sub>
  - [Determinar la iniciativa](#determinar-la-iniciativa)  <sub>pág. 18</sub>
  - [Turno de los personajes](#turno-de-los-personajes)  <sub>pág. 18-28</sub>
    - [Movimiento](#movimiento)  <sub>pág. 19</sub>
      - [Revelar una sala](#revelar-una-sala)  <sub>pág. 19</sub>
    - [Ataque](#ataque)  <sub>pág. 19-22</sub>
      - [Ventaja y desventaja](#ventaja-y-desventaja)  <sub>pág. 20-21</sub>
      - [Efectos de zona](#efectos-de-zona)  <sub>pág. 21</sub>
      - [Efectos de ataques](#efectos-de-ataques)  <sub>pág. 22</sub>
    - [Estados](#estados)  <sub>pág. 22-23</sub>
    - [Inducciones elementales](#inducciones-elementales)  <sub>pág. 23-24</sub>
    - [Bonificaciones activas](#bonificaciones-activas)  <sub>pág. 25-26</sub>
      - [Escudo](#escudo)  <sub>pág. 25</sub>
      - [Represalia](#represalia)  <sub>pág. 26</sub>
    - [Curación](#curación)  <sub>pág. 26</sub>
    - [Invocación](#invocación)  <sub>pág. 26</sub>
    - [Recuperación y reposición](#recuperación-y-reposición)  <sub>pág. 27</sub>
    - [Saqueo](#saqueo)  <sub>pág. 27</sub>
      - [Saqueo del final del turno](#saqueo-del-final-del-turno)  <sub>pág. 27</sub>
    - [Obtención de experiencia](#obtención-de-experiencia)  <sub>pág. 27-28</sub>
    - [Daño de los personajes](#daño-de-los-personajes)  <sub>pág. 28</sub>
    - [Agotamiento](#agotamiento)  <sub>pág. 28</sub>
    - [Objetos](#objetos)  <sub>pág. 28</sub>
  - [Turno de los monstruos](#turno-de-los-monstruos)  <sub>pág. 29-32</sub>
    - [Orden de actuación](#orden-de-actuación)  <sub>pág. 29</sub>
    - [Atención de los monstruos](#atención-de-los-monstruos)  <sub>pág. 29-30</sub>
    - [Movimiento de los monstruos](#movimiento-de-los-monstruos)  <sub>pág. 30-31</sub>
      - [Interacción de los monstruos con trampas y terreno peligroso](#interacción-de-los-monstruos-con-trampas-y-terreno-peligroso)  <sub>pág. 31</sub>
    - [Ataques de los monstruos](#ataques-de-los-monstruos)  <sub>pág. 31</sub>
    - [Otras capacidades de los monstruos](#otras-capacidades-de-los-monstruos)  <sub>pág. 31-32</sub>
    - [Ambigüedad](#ambigüedad)  <sub>pág. 32</sub>
    - [Jefes](#jefes)  <sub>pág. 32</sub>
  - [Final de la ronda](#final-de-la-ronda)  <sub>pág. 32</sub>
    - [Marcador de ronda](#marcador-de-ronda)  <sub>pág. 33</sub>
- [Terminar un escenario](#terminar-un-escenario)  <sub>pág. 33</sub>
- [Reglas especiales de los escenarios](#reglas-especiales-de-los-escenarios)  <sub>pág. 34</sub>
- [Descripción de la campaña](#descripción-de-la-campaña)  <sub>pág. 34-40</sub>
  - [Mapa de campaña](#mapa-de-campaña)  <sub>pág. 35</sub>
  - [Hoja de grupo](#hoja-de-grupo)  <sub>pág. 36</sub>
  - [Hoja de personaje](#hoja-de-personaje)  <sub>pág. 37</sub>
  - [Cartas de Misión personal](#cartas-de-misión-personal)  <sub>pág. 38</sub>
  - [Cartas de Diseño de objeto](#cartas-de-diseño-de-objeto)  <sub>pág. 38</sub>
  - [Cartas de Escenario secundario aleatorio](#cartas-de-escenario-secundario-aleatorio)  <sub>pág. 38</sub>
  - [Cartas de Evento de camino y de ciudad](#cartas-de-evento-de-camino-y-de-ciudad)  <sub>pág. 39</sub>
  - [Cajas y sobres cerrados](#cajas-y-sobres-cerrados)  <sub>pág. 40</sub>
  - [Anales de la ciudad](#anales-de-la-ciudad)  <sub>pág. 40</sub>
  - [Logros](#logros)  <sub>pág. 40</sub>
- [Jugar una campaña](#jugar-una-campaña)  <sub>pág. 41-47</sub>
  - [Viaje y eventos de camino](#viaje-y-eventos-de-camino)  <sub>pág. 41-42</sub>
    - [Completar eventos de camino](#completar-eventos-de-camino)  <sub>pág. 41-42</sub>
    - [Reputación](#reputación)  <sub>pág. 42</sub>
  - [Visitar Gloomhaven](#visitar-gloomhaven)  <sub>pág. 42-48</sub>
    - [Crear nuevos personajes](#crear-nuevos-personajes)  <sub>pág. 42</sub>
    - [Completar eventos de ciudad](#completar-eventos-de-ciudad)  <sub>pág. 43</sub>
    - [Comprar y vender objetos](#comprar-y-vender-objetos)  <sub>pág. 43</sub>
    - [Subir de nivel](#subir-de-nivel)  <sub>pág. 44-45</sub>
      - [Pericias adicionales](#pericias-adicionales)  <sub>pág. 44</sub>
      - [Crear una mano de cartas](#crear-una-mano-de-cartas)  <sub>pág. 45</sub>
      - [Adaptación de los escenarios](#adaptación-de-los-escenarios)  <sub>pág. 45</sub>
    - [Donar al Santuario](#donar-al-santuario)  <sub>pág. 45</sub>
    - [Mejorar cartas de Capacidad](#mejorar-cartas-de-capacidad)  <sub>pág. 45-47</sub>
    - [Anunciar la retirada de un personaje](#anunciar-la-retirada-de-un-personaje)  <sub>pág. 48</sub>
    - [Prosperidad de Gloomhaven](#prosperidad-de-gloomhaven)  <sub>pág. 48</sub>
  - [Completar un escenario](#completar-un-escenario)  <sub>pág. 49</sub>
- [Condiciones especiales para abrir sobres](#condiciones-especiales-para-abrir-sobres)  <sub>pág. 49</sub>
- [Variante de juego: aleatoriedad reducida](#variante-de-juego-aleatoriedad-reducida)  <sub>pág. 49</sub>
- [Variante de juego: muerte permanente](#variante-de-juego-muerte-permanente)  <sub>pág. 50</sub>
- [Variante de juego: mazo de Mazmorras aleatorias](#variante-de-juego-mazo-de-mazmorras-aleatorias)  <sub>pág. 50-51</sub>
- [Créditos](#créditos)  <sub>pág. 51</sub>
- [Guía rápida de iconos](#guía-rápida-de-iconos)  <sub>pág. 52</sub>

---

# Reglamento completo

<!-- pág. 4 -->

## Descripción del juego

La siguiente sección te enseñará las mecánicas para jugar un escenario individual, tomando como ejemplo el primer escenario del Libro de escenarios: El Túmulo Negro.

<!-- pág. 5 -->

### La zona de juego incluye

- Un tablero modular de piezas de Tablero (a) creado con una configuración concreta indicada en el Libro de escenarios (consulta [Preparación del escenario](#preparación-del-escenario) (las páginas 12-13)). Las piezas de Tablero deben colocarse de forma que queden conectadas mediante puertas (b). También deben colocarse las piezas de Terreno y los monstruos de la primera sala (c) junto con las figuras de los personajes.

- Una tarjeta de personaje por cada jugador (d) y la correspondiente mano de cartas de Capacidad para la clase de ese personaje (e), su dial de vida y experiencia (f), fichas de Personaje (g), una carta de Objetivo de batalla (h) boca abajo y cualesquiera cartas de Objeto (i) equipadas.

- Todas las cartas de Atributos de monstruo (j), con sus correspondientes figuras troqueladas, y las cartas de Capacidad de monstruo (k) puestas aparte en mazos individuales barajados.

- Mazos barajados de cartas de Modificador de ataque para cada jugador (l) y uno para los monstruos (m). Un mazo de Modificadores de ataque estándar está compuesto por 20 cartas, como se muestra en la parte superior de la página, y no por las cartas de Modificador específicas de cada personaje que vienen en las cajas de éstos. Sin embargo, un mazo podrá ser modificado mediante bonificaciones de subida de nivel, objetos, efectos del escenario y los efectos de los estados MALDICIÓN y BENDICIÓN.

- Montones de fichas de Daño (n), fichas de Dinero (o) y fichas de Estado (p).

- La tabla de inducción elemental (q) con los 6 elementos en la columna “Inerte”.

<!-- pág. 6 -->

### Tarjetas de personaje

Cuando un jugador comienza su epopeya en el juego, debe elegir una de las clases de personaje disponibles. Sólo puede jugarse una copia de cada clase de personaje en un mismo escenario. Cada clase tiene un conjunto de capacidades único, así que se trata de una decisión importante. Al abrir la caja del juego por primera vez, tendrás disponible al Salvaje [clase], al Manitas [clase], a la Tejedora de hechizos [clase], a la Pícara [clase], al Corazón hueco [clase] y a la Ladrona mental [clase].

Tras haber elegido una clase de personaje, el jugador coge la caja grande que tenga el símbolo de dicho personaje y saca la tarjeta de personaje correspondiente, las fichas de Personaje y la mano inicial de cartas de Capacidad de nivel 1 de ese personaje, así como la figura que se encuentra en la caja pequeña del personaje.

#### Una tarjeta de jugador incluye

- La imagen (a), el icono (b) y el nombre (c) de la clase.

- Indicadores de los puntos de vida máximos en cada nivel (d) de la clase. Los jugadores deben usar los diales (e) para llevar la cuenta de los puntos de vida (f) y de la experiencia (g) durante el escenario.

- La cantidad máxima de cartas de Capacidad que la clase puede llevar al combate (h).

- Una breve referencia (i) de la estructura de la ronda.

- Indicadores en el borde (j) de dónde colocar las cartas activas, perdidas y descartadas.

- El número de referencia de las cartas de Evento (k) añadidas a cada mazo cuando se desbloquea la clase del personaje (si no es parte de las 6 clases iniciales) y de las cartas de Evento (l) añadidas la primera vez que se retire la clase de ese personaje (consulta [Anunciar la retirada de un personaje](#anunciar-la-retirada-de-un-personaje) (la página 48)). Estos números de referencia se aplican tanto a los mazos de Eventos de ciudad como a los de camino.

<!-- pág. 7 -->

### Cartas de Capacidad de personaje

Jugar cartas de Capacidad permite a un personaje realizar acciones en un escenario. En cada ronda, los jugadores eligen 2 cartas de Capacidad y usan la acción superior de una carta y la acción inferior de la otra, de forma que cada jugador realice 2 acciones en su turno. Todas las cartas de Capacidad pertenecen a una clase de personaje concreta y se adquieren al crear un nuevo personaje o al subir de nivel.

#### Una carta de Capacidad incluye

- El nombre de la capacidad (a).

- Un número de iniciativa (b). El número de iniciativa de la carta principal jugada determina el orden del jugador en la iniciativa de una ronda concreta (consulta [Determinar la iniciativa](#determinar-la-iniciativa) (la página 18)).

- El nivel de la carta (c). Un personaje que empiece en el nivel 1 sólo puede usar sus cartas de nivel 1 (o también las cartas [nivel X]), pero obtendrá cartas más poderosas para añadirlas a su reserva de cartas de Capacidad disponibles a medida que suba de nivel.

- Una acción superior (d) y una acción inferior (e). Cuando se juegan las 2 cartas de Capacidad del turno de un jugador, una se usa por su acción superior y la otra por la inferior. Ten en cuenta que una misma acción puede contener varias capacidades (f) distintas (consulta [Turno de los personajes](#turno-de-los-personajes) (las páginas 18-28) sobre las acciones de los personajes).

<!-- pág. 8 -->

### Cartas de Objeto

Las cartas de Objeto se adquieren gastando oro entre un escenario y otro o saqueando piezas de Tesoro concretas. Todas las cartas de Objeto que equipe un personaje se colocarán por debajo de su tarjeta de personaje y podrán usarse durante una batalla para potenciar sus capacidades. Las cartas de Objeto no están vinculadas a una clase concreta, de forma que cualquier personaje podrá usar cualquier objeto. Sin embargo, los personajes tienen un límite a la cantidad de objetos que pueden equipar (llevar a un escenario). Cada personaje sólo puede equipar 1 objeto [cabeza], 1 objeto [cuerpo], 1 objeto [piernas], hasta 2 objetos [una mano] O BIEN 1 objeto [dos manos], y una cantidad de objetos [objeto pequeño] igual a la mitad de su nivel como máximo, redondeando hacia arriba. Los personajes no pueden poseer más de 1 copia de cualquier carta de Objeto.

#### Una carta de objeto incluye

- El nombre del objeto (a) y la cantidad de oro que debe pagar el personaje para adquirirlo en la tienda (b).

- Lo que ocurre con la carta tras usarla (c).

  - Este símbolo [gastar objeto] significa que el objeto se gasta tras usarlo, lo que se indica girando la carta hacia un lado. Las cartas gastadas se pueden reponer cuando un personaje realiza un descanso largo (consulta [Descanso](#descanso) (la página 17)). A veces, un objeto se usará varias veces antes de ser gastado o consumido. Esto se indica mediante espacios de uso (d) en la carta, cuya cuenta se lleva con una ficha de Personaje.

  - Este símbolo [objeto consumido] (no se muestra en la imagen) significa que el objeto es consumido tras usarlo, lo que se indica poniendo boca abajo la carta. Las cartas consumidas sólo pueden reponerse durante un escenario mediante capacidades concretas. Todos los objetos se reponen entre un escenario y otro. Ningún objeto se consume de forma permanente.

  - Si una carta no tiene ninguno de estos símbolos, no hay ninguna restricción respecto al número de veces que puede usarse durante un escenario, más allá de lo que aparezca escrito en el texto de la misma.

- Cuándo puede usarse el objeto y la bonificación obtenida por el personaje cuando se usa la carta de Objeto (e).

- El espacio de equipo (cabeza, cuerpo, piernas, una mano, dos manos, objeto pequeño) que ocupa el objeto (f).

- Algunos objetos equipados añaden al comienzo de un escenario una cantidad de cartas [modificador −1] al mazo de Modificadores de ataque del personaje que lo equipa. En este caso, la cantidad de cartas de Modificador se indica en el objeto (g).

- La cantidad de objetos iguales que hay en el juego (h) y cuál de ellos es éste (i).

- El número de referencia del objeto (j), que se encuentra en el dorso de la carta.

<!-- pág. 9 -->

### Cartas de Atributos de monstruo

Las cartas de Atributos de monstruo permiten consultar fácilmente los atributos básicos de un tipo de monstruo concreto, tanto para su variante normal como de élite. Los atributos básicos de un monstruo variarán en función del nivel del escenario (consulta [Nivel del escenario](#nivel-del-escenario) (la página 15)). Cada borde de estas cartas, en ambas caras, indica los atributos para un nivel de escenario concreto. Gira o dale la vuelta a la carta para mostrar el nivel correspondiente.

Debe usarse una funda de atributos de monstruo para llevar la cuenta del daño y de las fichas de Estado y para ocultar la información no necesaria de los niveles que no se usen.

#### Una carta de Atributos de monstruo incluye

- El nombre (a) y el nivel del conjunto de atributos (b) del monstruo correspondientes al nivel del escenario.

- Secciones para las versiones normal (c) y de élite (d) de este monstruo.

- El valor de puntos de vida (e) del monstruo, que es la cantidad de daño que hay que infligirle antes de que muera.

- El valor de movimiento (f) del monstruo, que es el número básico de hexágonos que puede moverse el monstruo con una acción de movimiento.

- El valor de ataque (g) del monstruo, que es la cantidad básica de daño que inflige el monstruo con una acción de ataque.

- El valor de alcance (h) del monstruo, que es el número básico de hexágonos desde el propio hexágono del monstruo que alcanza éste con un ataque o una curación. Si el valor de alcance es “–”, quiere decir que la acción de ataque normal del monstruo sólo puede tomar como objetivo los hexágonos adyacentes (es decir, un ataque cuerpo a cuerpo).

- Cualesquiera rasgos especiales que posea este tipo de monstruo (i). Estos rasgos son permanentes y se mantienen de ronda a ronda. Estos rasgos pueden incluir Vuelo, que se simboliza con (j) junto al nombre del monstruo (consulta [Movimiento](#movimiento) (la página 19)).

<!-- pág. 10 -->

### Cartas de Capacidad de monstruo

Cada ronda, después de que los jugadores hayan elegido sus cartas de Capacidad, se juega 1 carta por cada tipo de monstruo que haya en el tablero en ese momento (de los respectivos mazos de cartas de Capacidad de monstruo). Estas cartas determinan qué capacidades utilizará en su turno cada monstruo de ese tipo, tanto normal como de élite, durante la ronda.

#### Una carta de Capacidad de monstruo incluye

- El nombre del tipo de monstruo (a). A veces, varios tipos de monstruo emplean un mismo mazo de Capacidades más genérico. Por ejemplo, los Guardias bandido, los Guardias de la ciudad y los Guardias inox usan el mismo mazo de “Guardia”.

- Un número de iniciativa (b). Este número determinará cuándo actúa cada monstruo de ese tipo en una ronda determinada (consulta [Determinar la iniciativa](#determinar-la-iniciativa) (la página 18)).

- Una lista de capacidades (c). El monstruo utilizará cada una de estas capacidades en el orden indicado (si es posible) y luego terminará su turno (consulta [Turno de los monstruos](#turno-de-los-monstruos) (las páginas 29-32)).

- Un símbolo de devolución (d). Si aparece este símbolo en una carta, al final del turno debes devolver la pila de descartes de Capacidades del monstruo correspondiente a su mazo de robo y barajar éste.

### Cartas de Objetivo de batalla

Al comienzo de cada escenario, cada personaje recibe 2 cartas de Objetivo de batalla en secreto y elige quedarse 1 y descartar la otra. Si el escenario se completa con éxito y el personaje cumple los requisitos de la carta elegida (a), obtendrá el número de marcas que se indique en la parte inferior de la carta (b). Las marcas se emplean para mejorar el mazo de Modificadores de ataque del jugador (consulta [Pericias adicionales](#pericias-adicionales) (la página 44)). Si el escenario acabó en fracaso, el personaje no recibe nada por su carta de Objetivo de batalla, independientemente de si cumplió el objetivo o no. Los jugadores pueden usar notas para seguir el progreso de sus objetivos de batalla si es necesario, aunque deberían mantener sus objetivos de batalla en secreto unos de otros hasta que acabe el escenario.

<!-- pág. 11 -->

### Cartas de Modificador de ataque

En cualquier momento en el que se utilice una capacidad de ataque, se roba una carta de Modificador de ataque distinta para cada objetivo individual del ataque. Los jugadores roban estas cartas de su mazo de Modificadores de ataque personal, y los monstruos lo hacen de un mazo colectivo para los monstruos. A continuación, se aplica al ataque el modificador indicado en la carta, que podría reducir o aumentar su valor numérico.

#### Una carta de Modificador de ataque incluye

- El valor del modificador para el ataque (a). Un símbolo “nulo” (b) significa que el ataque no inflige daño alguno. Un símbolo “2x” (c) significa que se dobla el valor del ataque.

- Estados, inducciones elementales y otros efectos especiales del ataque (d). Si el modificador de ataque de la carta es +0, el efecto especial se muestra en el círculo central de la carta (e). Si no es así, se muestra a la izquierda del valor del modificador (f). Cuando se activan estos efectos especiales, funcionan exactamente igual que si aparecieran escritos en la carta de la acción que se usa para el ataque. (d)

- El símbolo del modificador de racha (g) indica que debe robarse una carta de Modificador adicional. Se seguirán robando cartas de Modificador hasta que dejen de revelarse símbolos de racha, en cuyo momento se sumarán todos los modificadores robados.

Añade a tu ataque “EMPUJÓN 2” y los efectos del elemento tierra y luego aumenta en 2 tu valor de ataque.

- Un borde especial de BENDICIÓN (h) o MALDICIÓN (i). Si se roba (h) una carta de BENDICIÓN o MALDICIÓN, debe retirarse del mazo del jugador en lugar de ponerla en el descarte. Las cartas de maldición también tienen un símbolo [monstruo] o [personaje] para indicar si se pueden colocar en el mazo de Modificadores de ataque de los monstruos [monstruo] o en el mazo de Modificadores de ataque de un personaje [personaje].

- Un símbolo de devolución (j). Al final de una ronda en la que se haya robado de un mazo una carta “nulo” [nulo] o “2x” [2x], los jugadores deben devolver a dicho mazo todas las cartas de Modificador jugadas de ese mazo concreto. También se devuelven todas las cartas al mazo y se barajan si hay que robar una carta de Modificador y no queda ninguna en el mazo de robo.

- Un icono de tipo (k). Todos los mazos de Modificadores estándar tienen un icono 1, 2, 3, 4 o M (l) para poder clasificarlos fácilmente, ya que todas las cartas con un mismo icono forman el mazo estándar de 20 cartas. Todas las cartas añadidas por una clase de personaje a su mazo de Modificadores mediante pericias (consulta [Subir de nivel](#subir-de-nivel) (las páginas 44-45)) tienen el símbolo de esa clase de personaje (m). Las cartas añadidas a un mazo de Modificadores mediante el efecto de un escenario o de un objeto tienen un icono (n). Debes retirar estas cartas al final del escenario. (k)

<!-- pág. 12 -->

## Preparación del escenario

Al preparar un nuevo escenario, el primer paso es mirar el Libro de escenarios para colocar las piezas de Tablero y reunir todos los tipos de monstruo con los que combatirás. A continuación, debes leer el texto de la introducción y aplicar cualesquiera efectos negativos del escenario que aparezcan en la sección “Reglas especiales”. Después, reparte 2 objetivos de batalla a cada jugador, que descartará uno de ellos. El siguiente paso es que los jugadores decidan qué objetos quieren equipar de entre la colección de objetos que posean (añadiendo cartas –1 a sus mazos de Modificadores de ataque cuando sea necesario). Luego deben decidir qué cartas de Capacidad quieren añadir a su mano, eligiendo de entre la reserva de cartas que tengan disponibles. Cada jugador debe elegir una cantidad de cartas igual al límite de mano de su personaje. Al jugar por primera vez, la mano de un jugador sólo estará formada por el conjunto de cartas de Capacidad de nivel 1 [nivel 1] de la clase del personaje. Cuando el jugador se haya familiarizado con la clase, puede empezar a sustituir cartas de nivel 1 por cartas más complejas que tengan nivel [nivel X]. Cuando el personaje comience a subir de nivel, también tendrá acceso a cartas de nivel superior que podrá añadir a su mano en sustitución de otras. Después de que los jugadores hayan elegido su mano de cartas, se aplican, si los hay, los efectos de cualquier evento de camino o de ciudad que haya acontecido antes del escenario (consulta [Viaje y eventos de camino](#viaje-y-eventos-de-camino) (la página 41)).

### Página de escenario

#### Una página de escenario incluye

- El nombre (a), número de referencia (b) y coordenadas (c) del escenario, además de la casilla para marcar que el escenario ha sido completado.

- Posibles logros (d) necesarios para jugar el escenario en una campaña.

- Las condiciones de victoria (e).

- Al jugar el escenario como parte de la campaña, la página proporciona un texto de introducción (f), elementos de la historia adicionales (g) que se leen al entrar en el hexágono correspondiente del tablero (h) y un texto de conclusión (i) que debe leerse al cumplir las condiciones de victoria.

- El nombre, número de referencia y coordenadas de la ubicación de cualquier escenario nuevo (j) que se desbloquee al completar el escenario como parte de una campaña.

- Cualquier otra recompensa (k) obtenida por completar el escenario durante una campaña.

<!-- pág. 13 -->

- Cualquier ubicación con la que esté conectada el escenario ((l); consulta [Viaje y eventos de camino](#viaje-y-eventos-de-camino) (las páginas 41-42)).

- La configuración de piezas de Tablero (m) y de Puerta (n) que deben colocarse durante la preparación. También se indican las piezas de Tablero concretas que se necesitan para cada escenario (o). El tablero de cada escenario se divide en salas distintas mediante piezas de Terreno de puerta. Una sala puede componerse de más de una pieza de Tablero si dichas piezas están conectadas por otras piezas de Terreno.

- Indicaciones que se emplean para poblar el tablero del escenario (p) según la clave de colocación de los monstruos (q). Estas indicaciones pueden aparecer en dos orientaciones distintas según la orientación general del tablero. La clave de colocación de los monstruos consiste en tres secciones impresas sobre el símbolo del monstruo: la superior izquierda indica la colocación para dos personajes, la superior derecha para tres personajes y la inferior para cuatro personajes. NEGRO significa que el monstruo no se coloca para el número de personajes correspondiente, BLANCO que el monstruo es normal y AMARILLO que es de élite. Los monstruos normales deben colocarse en el

> **Leyenda de la clave de monstruos.** Negro: monstruo no presente · blanco: monstruo normal · amarillo: monstruo de élite.

> **Ejemplo.** [clave] indica qué tipo de monstruo se coloca en este hexágono: en este caso el monstruo no se coloca para dos personajes, es normal para tres personajes y es de élite para cuatro personajes.
tablero con sus correspondientes figuras troqueladas sobre bases blancas, y los de élite sobre bases amarillas.

Ten en cuenta que, al comienzo de un escenario, sólo se colocan los monstruos de la sala inicial. Cada figura troquelada de monstruo tiene un número para determinar el orden en el que actúa durante el turno (consulta [Orden de actuación](#orden-de-actuación) (la página 29)). Aleatoriza los números de las figuras al colocarlas.

- Las ubicaciones iniciales disponibles para los personajes, indicadas mediante (r). Los jugadores pueden elegir colocar sus figuras en cualquier hexágono [ubicación inicial] vacío al comienzo del escenario.

- El tipo de trampas empleadas en este escenario (s) y la recompensa por saquear piezas de Tesoro en el tablero (t). Los números de los tesoros aparecen al final del Libro de escenarios, para que las recompensas se mantengan en secreto.

- Ubicaciones de las fichas de Dinero (u) y de Terreno (v) que deben colocarse en el tablero cuando se revele la pieza de la sala.

<!-- pág. 14 -->

### Piezas de Terreno

El Libro de escenarios recoge el conjunto de piezas de Tablero que se emplearán en cada escenario; además, existen fichas de Terreno especiales que sirven para darle forma al encuentro.

#### Tipos de piezas de Terreno

- Puertas [puerta]: las puertas sirven como separación entre dos salas. Cuando un personaje se mueve a una pieza de puerta cerrada, le da inmediatamente la vuelta para mostrar su lado abierto y revela el contenido de la pieza de la sala adyacente. Coloca inmediatamente las piezas de Terreno, los monstruos y las fichas de Dinero según indique la descripción del escenario para la sala revelada. Aunque las puertas cerradas no obstaculizan en absoluto el movimiento de los personajes, sí que actúan como una pared para cualquier monstruo o figura invocada por los personajes; tampoco es posible obligar a una figura a atravesar una puerta cerrada. Las puertas abiertas no obstaculizan ningún tipo de movimiento y no se pueden cerrar. La ilustración de la puerta es distinta según el tipo de entorno, pero todas tienen el mismo funcionamiento.

- Pasillos [pasillo]: los pasillos se colocan en la conexión de dos piezas de Tablero para tapar las paredes y crear una sola sala compuesta por varias piezas de Tablero. Los pasillos funcionan como hexágonos vacíos normales.

- Trampas [trampa]: las trampas se activan cuando una figura entra en su hexágono mediante un movimiento normal u obligado. Los movimientos de Vuelo [vuelo] y de Salto [salto] no se ven afectados por las trampas. Cuando se activa una trampa, inflige un efecto negativo a la figura que la ha activado y luego se retira del tablero. Las trampas también se pueden desactivar mediante acciones concretas para retirarlas del tablero sin sufrir sus efectos negativos. Los efectos de las trampas son muy variados y se detallan en el Libro de escenarios. Si parte del efecto de una trampa se indica como “daño”, la trampa infligirá 2+N puntos de daño a la figura afectada, donde N es el nivel del escenario. Los personajes y los monstruos también pueden crear trampas en el tablero, con los efectos indicados por la capacidad que crea la trampa. Siempre que se coloque una trampa en el tablero, deben colocarse sobre la pieza de la misma las fichas del daño y los efectos que inflija ésta para que sea fácil identificarlos.

- Terreno peligroso [terreno peligroso]: si una figura entra en un hexágono que tenga terreno peligroso mediante un movimiento normal u obligado, cada hexágono infligirá la mitad de daño que una trampa (redondeando hacia abajo). Los movimientos de Vuelo [vuelo] y de Salto [salto] no se ven afectados por el terreno peligroso. A diferencia de las trampas, el terreno peligroso no es retirado después de aplicar su efecto, sino que permanece en el tablero indefinidamente. Empezar un turno en estos hexágonos o salir de ellos no inflige daño adicional.

- Terreno impracticable [terreno impracticable]: para entrar en un hexágono con terreno impracticable, una figura necesita 2 puntos de movimiento normal. Los movimientos obligados, de Vuelo [vuelo] y de Salto [salto] no se ven afectados por el terreno impracticable.

- Obstáculos [obstáculo]: los obstáculos tienen distintas ilustraciones, pero todos funcionan del mismo modo. Las figuras no pueden atravesar obstáculos con un movimiento normal, pero sí pueden hacerlo con un movimiento de Vuelo [vuelo] o de Salto [salto]. Estas piezas no obstaculizan los ataques a distancia. Es posible que las capacidades de algunos personajes creen obstáculos o los muevan. Al hacerlo, los jugadores no pueden aislar completamente una zona del tablero del escenario del resto; es decir, no pueden crear una zona a la que no se pueda entrar sin atravesar obstáculos.

<!-- pág. 15 -->

- Tesoro [tesoro]: los jugadores pueden saquear las piezas de Tesoro (consulta [Saqueo](#saqueo) (la página 27)), lo que puede producir distintos efectos. Hay dos tipos de piezas de Tesoro: piezas de “objetivo” y piezas numeradas. Las piezas de objetivo son importantes para poder completar un escenario, y las reglas para saquearlas las indicará el escenario. Estas piezas se reiniciarán cada vez que se juegue un escenario. Por otro lado, las piezas numeradas pueden proporcionar distintos beneficios. Al saquear una, el jugador que lo hace debe consultar el número de la pieza en el índice de tesoros que hay al final del Libro de escenarios para ver lo que ha encontrado. Si se indica un nombre de objeto concreto, búscalo en el mazo de Objetos únicos y añádelo inmediatamente a tu reserva de objetos. Si el nombre de objeto va precedido de la palabra “diseño”, busca todas las copias de ese objeto y añádelas a la reserva disponible de la ciudad. Las piezas de Tesoro numeradas sólo se pueden saquear una vez. Después de haberlas saqueado, es necesario tacharlas en el Libro de escenarios como recordatorio.

### Nivel del escenario

Los atributos básicos de los monstruos, el daño de las trampas, la cantidad de oro recibida por las fichas de Dinero y la cantidad de experiencia extra por completar un escenario dependen del nivel del escenario que se esté jugando. El nivel del escenario lo eligen los jugadores antes de comenzar éste, y está basado en el nivel medio del grupo y en la dificultad que quieran que tenga el escenario.

El nivel de un escenario puede fijarse en cualquier número entre 0 y 7, pero no se puede cambiar una vez que haya comenzado el escenario. El nivel de escenario recomendado es igual al nivel medio de los personajes del grupo, dividido entre 2 y redondeado hacia arriba; a esto se le consideraría dificultad “Normal”. Si los jugadores quieren una experiencia “Fácil”, pueden reducir en 1 el nivel de escenario recomendado. Si prefieren una experiencia más difícil, pueden aumentar en 1 el nivel del escenario para que sea “Difícil”, o en 2 para que sea “Muy difícil”.

| Dificultad | Modificación de nivel |
|---|---|
| Fácil | -1 |
| Normal | +0 |
| Difícil | +1 |
| Muy difícil | +2 |

| Nivel del escenario | Nivel de los monstruos | Conversión de oro | Daño de las trampas | Experiencia extra |
|---|---|---|---|---|
| 0 | 0 | 2 | 2 | 4 |
| 1 | 1 | 2 | 3 | 6 |
| 2 | 2 | 3 | 4 | 8 |
| 3 | 3 | 3 | 5 | 10 |
| 4 | 4 | 4 | 6 | 12 |
| 5 | 5 | 4 | 7 | 14 |
| 6 | 6 | 5 | 8 | 16 |
| 7 | 7 | 6 | 9 | 18 |

Ejemplo: si un grupo contiene un personaje de nivel 6, dos personajes de nivel 4 y un personaje de nivel 3, la media sería 4,25; tras dividirla entre 2 y redondearla, el resultado es 3, que sería el nivel de dificultad normal del escenario. La elección del nivel del escenario depende completamente de los jugadores. Los niveles de escenario más altos dan lugar a la aparición de monstruos más difíciles, pero también otorgan más oro y experiencia.

<!-- pág. 16 -->

### Variante de juego: información pública y juego en solitario

Un jugador puede jugar en solitario si controla 2 o más personajes a la vez. Sin embargo, parte de la dificultad del juego se deriva de no saber exactamente qué harán los demás personajes durante su turno. Puesto que un jugador en solitario tiene información precisa sobre lo que hará cada personaje y puede coordinarlos de forma más eficaz, el juego se vuelve más fácil. Para compensarlo, los jugadores que jueguen en solitario deben aumentar en 1 el nivel de los monstruos y el daño de las trampas para cualquier escenario, sin aumentar la conversión de oro y la experiencia extra.

Además, un grupo de jugadores puede elegir jugar compartiendo toda la información de forma pública si aumenta la dificultad del mismo modo que lo haría un jugador en solitario. Jugar con información pública significa que los jugadores pueden compartir el contenido exacto de su mano y comentar los detalles de lo que quieren hacer. Ésta no es la forma recomendada de jugar al juego, pero algunos grupos podrían preferir hacerlo así.

## Descripción de la ronda

Un escenario se compone de una serie de rondas que se juegan hasta que los jugadores cumplan las condiciones de victoria del escenario o fracasen. Una ronda se compone de estos pasos:

1. Selección de cartas: cada jugador elegirá 2 cartas de su mano para jugarlas o bien declarará que va a realizar una acción de descanso largo durante la ronda.

2. Determinar la iniciativa: los jugadores revelan sus cartas para la ronda, y también se revela 1 carta de Capacidad para cada tipo de monstruo que esté revelado en ese momento. A continuación, se determina el orden de iniciativa en función de los valores de iniciativa de las cartas reveladas.

3. Turnos de los personajes y los monstruos: empezando por la iniciativa más baja, los jugadores y los monstruos llevan a cabo sus turnos y realizan las acciones de sus cartas, con las posibles modificaciones que apliquen las cartas de Objeto de los personajes.

4. Limpieza: es posible que haya que reorganizar o retirar elementos al final de la ronda (consulta [Final de la ronda](#final-de-la-ronda) (la página 32)).

### Selección de cartas

Al comienzo de una ronda, cada jugador elige 2 cartas de su mano en secreto y las juega boca abajo frente a él. De las 2, debe elegir 1 como carta principal, que determinará el orden del jugador en la iniciativa de la ronda (consulta [Determinar la iniciativa](#determinar-la-iniciativa) (la página 18)).

<!-- pág. 17 -->

Ningún jugador debe mostrarle al resto las cartas que tiene en la mano ni dar información concreta sobre el nombre o algún valor numérico de ninguna de sus cartas. Sin embargo, sí puede realizar afirmaciones generales sobre sus acciones en la ronda y comentar cualquier estrategia.

- Ejemplos de comunicación válida: “Voy a atacar a este guardia hacia la mitad de la ronda”. “Quiero moverme aquí y curarte muy al principio de la ronda, esperemos que antes de que ataquen los monstruos”.

- Ejemplos de comunicación no válida: “Necesitarás una iniciativa menor que 17 para actuar antes que yo”. “Probablemente le haré 4 puntos de daño al bandido, así que no tienes que preocuparte por él”. “Voy a usar Erupción empaladora para acabar con todos”.

Durante el turno de un jugador, las dos cartas jugadas se usan para realizar acciones y luego se descartan, pierden o activan, según las acciones que se hayan realizado. Por lo general, las cartas se colocan en la pila de descartes del jugador salvo que se indique algo distinto. Las cartas descartadas se pueden devolver a la mano del jugador mediante el descanso (ver a continuación). Si la acción realizada de la carta contiene un símbolo [perdida] en la parte inferior derecha del campo de acción, la carta se coloca en la pila de pérdida del jugador en lugar de en la pila de descartes. Las cartas perdidas sólo pueden volver a la mano del jugador durante un escenario si se usa una acción de recuperar especial. Tanto si la carta correspondiente se descarta como si se pierde, algunas acciones pueden contener un efecto activo (indicado por los símbolos que hay a la derecha). En lugar de colocarse en la pila de descartes o de pérdida, la carta se coloca en la zona activa frente al jugador para tener en cuenta el efecto. Cuando el efecto acabe, la carta pasará a la pila correspondiente (consulta [Bonificaciones activas](#bonificaciones-activas) (las páginas 25-26)).

Los jugadores deben jugar 2 cartas de su mano o declarar una acción de descanso largo al comienzo de cada ronda. Si un jugador sólo tiene 1 carta en la mano o si no tiene cartas, su única opción será la acción de descanso largo. Si esta opción tampoco está disponible al comienzo de una ronda porque el jugador también tiene sólo 1 carta o ninguna en la pila de descartes, se considera que el jugador está agotado y no puede seguir participando en el escenario (consulta [Agotamiento](#agotamiento) (la página 28)).

#### Descanso

El descanso es la principal herramienta que tienen los jugadores para poder devolver cartas descartadas a su mano de cartas disponibles. Al descansar, los jugadores tienen 2 opciones: un descanso corto o un descanso largo. En ambos casos, la acción de descanso sólo se puede realizar si el jugador tiene 2 o más cartas en su pila de descartes, y una acción de descanso siempre tiene como resultado la pérdida de 1 de las cartas descartadas.

- Descanso corto: durante el paso de limpieza de una ronda, los jugadores pueden realizar un descanso corto. Esto permite a un jugador barajar su pila de descartes inmediatamente y luego coger al azar 1 de las cartas y colocarla en su pila de pérdida; a continuación, devuelve el resto de las cartas descartadas a su mano. Si el jugador quiere conservar la carta que perdió al azar, puede elegir sufrir 1 punto de daño y elegir al azar una carta descartada distinta para perderla. Esto sólo puede hacerse una vez por descanso.

- Descanso largo: un descanso largo se declara durante el paso de selección de cartas de la ronda y emplea todo el turno del jugador en esa ronda. Se considera que el valor de iniciativa de los jugadores que realizan este descanso es 99. En el turno del jugador que descansa, al final del orden de iniciativa, debe elegir 1 de sus cartas descartadas para perderla y luego devolver el resto de las cartas descartadas a su mano. El personaje que descansa también realiza una acción de “Curación [curación] 2, Personal” y repone todas sus cartas de Objeto gastadas.

<!-- pág. 18 -->

### Determinar la iniciativa

Después de que los jugadores hayan elegido sus 2 cartas de Capacidad o declarado un descanso largo, los jugadores revelan 1 carta de Capacidad de monstruo para cada tipo de monstruo que tenga al menos una figura en el tablero en ese momento. Además, cada jugador que no esté realizando un descanso largo revela sus cartas seleccionadas para la ronda, colocando su carta principal encima, de forma que su valor de iniciativa sea visible.

El orden de iniciativa se determina al comparar los valores de iniciativa de todas las cartas de Capacidad de monstruo jugadas y de todas las cartas principales de los jugadores. Quien tenga el valor de iniciativa más bajo jugará el primer turno, seguido por quien tenga el siguiente valor más alto, y así sucesivamente hasta que hayan actuado todas las figuras del tablero. Cuando un tipo de monstruo tenga que realizar una acción, cada monstruo de ese tipo realizará las acciones indicadas en su carta de Capacidad jugada, empezando por los monstruos de élite y siguiendo por los normales en orden ascendente.

Si se produce un empate de iniciativa entre los jugadores, mira la carta no principal de cada jugador para resolver el desempate. Si sigue habiendo empate, los jugadores deberán decidir entre ellos quién actúa primero. Si se produce un empate entre un jugador y un tipo de monstruo, el jugador actúa primero. Si se produce un empate entre dos tipos de monstruo, los jugadores deciden cuál actúa primero.

Ejemplo: al comienzo de la ronda, el Salvaje decide que quiere jugar las 2 cartas que se muestran en la imagen. También decide que quiere actuar hacia el final de la ronda, por lo que elige “61” como su carta principal. Si hubiera querido actuar hacia el comienzo de la ronda, podría haber elegido “15” como su carta principal. La Pícara revela una carta principal con una iniciativa de “86”, y las cartas de Capacidad de monstruo jugadas para los Huesos vivientes y las Arqueras bandidas tienen una iniciativa de “45” y “32” respectivamente. Las Arqueras bandidas se activan primero, luego lo hacen todos los Huesos vivientes, después iría el Salvaje y, por último, la Pícara.

### Turno de los personajes

En el turno de un personaje, éste realizará la acción superior de una de las dos cartas de Capacidad jugadas y la inferior de la otra. La elección de la carta principal que se empleó para determinar la iniciativa ya no tiene ningún efecto. Los jugadores pueden jugar cualquiera de las dos cartas en primer lugar y resolver su acción superior o inferior. Al jugar la acción de la carta, las capacidades de dicha acción deben realizarse en el orden en el que aparecen y no pueden interrumpirse mediante la acción de la otra carta. Una vez que se ha completado la acción de de una carta, se coloca inmediatamente en la zona apropiada (pila de descartes, pila de pérdida o zona activa) antes de que ocurra nada más. Por lo general, los jugadores son libres de elegir no realizar alguna parte de la acción de su carta; sin embargo, deben realizar cualquier parte que tenga un efecto negativo (por ejemplo, reducir los puntos de vida, perder cartas o sufrir un estado negativo) sobre sí mismos o sus aliados. Un aliado es cualquier figura que luche junto a un personaje; este término incluye las figuras invocadas, pero no al

propio personaje. Las capacidades no pueden afectar a los aliados a carta o las reglas especifiquen algo distinto. Los jugadores también pueden usar cualquier carta que jueguen como una acción “Ataque 2” en la mitad superior o una acción “Movimiento 2” en la inferior. Si una carta se usa de este modo, siempre se descarta, independientemente de lo que haya impreso en ella. Durante su turno, antes, durante o después de realizar sus dos acciones, los jugadores pueden usar cualquier cantidad de objetos que tengan equipados.

<!-- pág. 19 -->

#### Movimiento

Una capacidad “Movimiento X” permite a un personaje moverse un máximo de X hexágonos en el tablero. Las figuras (personajes y monstruos) pueden moverse a través de aliados, pero no a través de enemigos u obstáculos. Las trampas y otros efectos del terreno de los hexágonos deben resolverse cuando una figura entra en ellos mediante un movimiento normal. Una figura no puede acabar su movimiento en el mismo hexágono que otra figura. Las figuras nunca pueden moverse a través de paredes.

Algunas capacidades de movimiento aparecen indicadas como “Salto”. Las capacidades “Movimiento X (Salto)” permiten a un personaje ignorar todas las figuras y efectos del terreno durante su movimiento. Sin embargo, el último hexágono del salto se considera un movimiento normal, por lo que debe seguir las reglas de movimiento normal que aparecen en el párrafo anterior.

Algunas figuras podrían tener el rasgo especial “Vuelo”. Esto permite a las figuras ignorar por completo todas las figuras y piezas de Terreno durante cualquier parte de su movimiento, incluido el último hexágono, con la excepción de que siguen debiendo acabar su movimiento en un hexágono sin ocupar (que no contenga figuras). Esto incluye movimientos obligados como EMPUJÓN o TIRÓN. Si una figura pierde su rasgo “Vuelo” mientras ocupa un hexágono de obstáculo, recibe daño como si hubiera activado una trampa de daño y luego se mueve inmediatamente al hexágono vacío más cercano (sin figuras, fichas ni piezas de Terreno de ningún tipo, excepto pasillos, placas de presión y puertas abiertas).

##### Revelar una sala

Durante cualquier parte del movimiento de un personaje, si éste entra en una pieza que tenga una puerta cerrada, dale la vuelta a la puerta para mostrar su lado abierto y revela inmediatamente la sala adyacente que haya al otro lado. El Libro de escenarios indicará qué monstruos, fichas de Dinero y piezas de Terreno especiales deben colocarse en la sala revelada en función del número de personajes (incluidos los agotados). Ten en cuenta que, al igual que durante la preparación del escenario, los números de las figuras de los monstruos de la nueva sala deben aleatorizarse al colocarlos. Es posible quedarse sin figuras de algún tipo de monstruo concreto al revelar una sala; si ocurre esto, coloca sólo las figuras que haya disponibles, empezando por los monstruos más cercanos al personaje que esté revelando la sala.

Tras haberlo colocado todo en la nueva sala, debe robarse 1 carta de Capacidad para cualquier tipo de monstruo presente que no tenga una. Cuando acabe el turno del personaje que ha revelado la sala, se revisan los valores de iniciativa de todos los monstruos de la nueva sala, y cualquier tipo de monstruo que tenga un valor de iniciativa menor que el personaje que ha revelado la sala (es decir, que hubiera debido actuar antes en la ronda) debe realizar su turno inmediatamente (en el orden de iniciativa normal en caso de que haya varios tipos de monstruo en esta situación). De esta forma, todos los monstruos revelados en la nueva sala siempre completarán un turno en la ronda en la que son revelados.

#### Ataque

Una capacidad “Ataque X” permite a un personaje infligirle una cantidad básica de daño X a un enemigo que esté dentro de su alcance. Las figuras no pueden atacar a sus aliados. Hay dos tipos de ataques: a distancia y cuerpo a cuerpo.

Los ataques a distancia van acompañados de un valor “Alcance Y”, que significa que cualquier enemigo a Y o menos hexágonos de distancia puede ser objetivo del ataque. Cualquier ataque a distancia que tenga como objetivo un enemigo adyacente está en desventaja contra ese objetivo (consulta [Ventaja y desventaja](#ventaja-y-desventaja) (las páginas 20-21)).

Los ataques cuerpo a cuerpo no tienen ningún valor de alcance, y se considera que tienen un alcance predeterminado de 1 hexágono; esto significa que, por lo general, tendrán como objetivo enemigos adyacentes.

Línea de visión: para poder realizar cualquier ataque cuerpo a cuerpo o a distancia, es necesario que el enemigo objetivo esté dentro de la línea de visión; es decir, que debe poder trazarse una línea desde cualquier esquina del hexágono del atacante hasta cualquier esquina de hexágono del defensor sin que toque ninguna parte de una pared (la línea del borde de una pieza de Tablero <!-- pág. 20 --> o toda la zona de cualquier hexágono parcial que vaya por el borde de una pieza de Tablero, salvo que esté tapada por una pieza de Terreno). Las paredes son lo único que bloquea la línea de visión. Además, cualquier capacidad que especifique un alcance sólo podrá emplearse sobre figuras que estén dentro de la línea de visión. Si una capacidad que no sea un ataque no especifica alcance alguno, no es necesaria línea de visión. También es necesario tener en cuenta que dos hexágonos separados por una línea de pared no se consideran adyacentes, y que no puede contarse el alcance a través de paredes.

Al atacar, el valor básico de ataque escrito en la carta puede ser modificado por tres tipos de valores en el siguiente orden. Repite estos pasos por cada enemigo individual que sea objetivo del ataque:

- En primer lugar se aplican los modificadores de ataque del atacante. Estos modificadores incluyen bonificaciones y penalizaciones de las cartas de Capacidad activas, de objetos y de otros elementos (por ejemplo, Ataque +1 por VENENO).

- A continuación, se roba y se aplica una carta de Modificador de ataque del mazo de Modificadores de ataque del atacante.

- Por último, se aplican las bonificaciones defensivas del defensor. Esto reduce el valor de ataque que recibe cada enemigo individual objetivo del ataque en función del modificador de escudo de cada defensor o de otras bonificaciones defensivas.

- Si hay varios modificadores en cualquiera de los pasos de este proceso, el jugador elige el orden en el que se aplican. Ten en cuenta también que, puesto que las bonificaciones se aplican por objetivo, es posible que la misma acción de ataque acabe infligiendo una cantidad distinta de daño a cada enemigo que tenga por objetivo.

Ejemplo: la Pícara utiliza una capacidad de “Ataque 3” contra un Guardia bandido de élite adyacente. La Pícara añade un modificador de ataque +2 debido a las condiciones que establece la carta, y también puede doblar el ataque gracias a una carta activa que tiene frente a ella. Elige añadir el +2 y luego doblar el resultado, lo que da un “Ataque 10”. A continuación, juega una carta de Modificador de ataque y revela un “–1”, de forma que el ataque se reduce a 9. Por último, el Guardia bandido tiene un valor de escudo de 1, por lo que el valor de ataque se reduce a 8 y el enemigo sufre 8 puntos de daño.

Cualquier daño sufrido por un monstruo debe registrarse en la funda de atributos, en la sección correspondiente al número de la figura del monstruo afectado. Cuando se reducen los puntos de vida de un monstruo a 0 o menos por un ataque o cualquier otra forma de daño, el monstruo muere inmediatamente y es retirado del tablero. Cuando un monstruo muere, no se aplican los posibles efectos adicionales del ataque.

Cuando un monstruo muere, también se coloca 1 ficha de Dinero en el hexágono donde murió si el monstruo no había aparecido ni sido invocado.

##### Ventaja y desventaja

Algunos ataques pueden tener ventaja o estar en desventaja.

- Un atacante que tenga la ventaja robará 2 cartas de Modificador de su mazo y usará la que sea mejor (a). Si se roba 1 carta de Modificador de racha, su efecto se suma a la otra carta jugada (b). Si se roban 2 cartas de Modificador de racha, sigue robando cartas hasta que dejes de robar rachas y luego suma todos los efectos robados (c).

(a) (b) (c) Un atacante que esté en desventaja robará 2 cartas de Modificador de su mazo y usará la que sea peor (d). Cuando se está en desventaja, se ignoran los Modificadores de racha (e). Si se roban 2 cartas de Modificador de racha, sigue robando cartas hasta que dejes de robar rachas y luego aplica únicamente el efecto de la última carta robada (f).

Ejemplo de una capacidad que concede la ventaja.

<!-- pág. 21 -->

Si no está claro cuál de las dos cartas robadas es mejor o peor, usa la que se robara en primer lugar. Esta ambigüedad puede producirse al comparar uno o más efectos añadidos proporcionados por las cartas de Modificador de ataque (por ejemplo, inducciones elementales, estados negativos, etc.). Todos los efectos añadidos deben considerarse como si tuvieran un valor numérico positivo, pero no definido.

Tener ventaja o estar en desventaja suele ser consecuencia de capacidades concretas de los personajes o los monstruos. Sin embargo, cualquier ataque a distancia que tenga como objetivo un enemigo adyacente estará en desventaja para ese objetivo. No es posible acumular casos de tener ventaja o estar en desventaja, y si un ataque tiene ventaja y está en desventaja a la vez, ambos efectos se cancelan mutuamente y el ataque se realiza de forma normal.

##### Efectos de zona

Algunos ataques y capacidades permiten a las figuras tener varios objetivos o tomar como objetivo varios hexágonos a la vez. En estos casos, la zona de efecto de la capacidad se muestra en la carta de Capacidad. Ten en cuenta que la imagen mostrada puede aplicarse girándola con cualquier orientación. Además, aunque cada objetivo tomado es parte de un ataque distinto (y por tanto se roba para él su propia carta de Modificador de ataque), todos los ataques forman una sola acción de ataque.

(a) El color gris indica el hexágono en el que se encuentra la figura en ese momento. Un ataque de zona que incluya un hexágono gris siempre se considera un ataque cuerpo a cuerpo.

(b) El color rojo indica los hexágonos con los enemigos afectados por la capacidad.

Para un ataque de zona a distancia, sólo es necesario que uno de los hexágonos rojos esté dentro del alcance indicado, y no hace falta que contenga un enemigo. Sin embargo, sólo puedes atacar enemigos que estén en de hexágonos para los que tengas líneas de visión tanto en ataques a distancia como cuerpo a cuerpo.

Ejemplo: este ataque indica que la figura puede realizar un “Ataque 4” a distancia sobre un grupo de 3 hexágonos siempre que al menos uno de esos hexágonos esté a alcance 3 o menos.

Ejemplo: este ataque indica que la figura puede realizar un “Ataque 3” cuerpo a cuerpo sobre un grupo de 3 hexágonos.

Algunos ataques van acompañados por un valor “Objetivo X”, lo que significa que el personaje puede tomar como objetivo X enemigos diferentes que estén dentro del alcance del ataque.

En cualquier ataque que tenga como objetivo varios enemigos, se roba 1 carta de Modificador de ataque por cada objetivo. No es posible tomar como objetivo el mismo enemigo con varios ataques realizados con la misma capacidad. Nota: las capacidades nunca pueden tomar aliados como objetivo (las capacidades positivas que van dirigidas a aliados usan el término “afectar” en lugar de “objetivo”). Un aliado puede estar dentro de la zona afectada por un ataque, pero no será objetivo del mismo.

También hay que tener en cuenta que siempre que un ataque no especifique un alcance, se considera cuerpo a cuerpo, por lo que es posible atacar con un ataque cuerpo a cuerpo a un objetivo que no esté adyacente si la configuración de hexágonos así lo permite.

<!-- pág. 22 -->

##### Efectos de ataques

Las capacidades de ataque a menudo tendrán efectos que aumentan su potencia. Si una carta de Capacidad tiene un efecto de ataque impreso después de un ataque, el objetivo u objetivos del ataque también sufrirán el efecto adicional después de resolver el daño del ataque. Los efectos de ataque se aplican independientemente de que el ataque correspondiente inflija daño o no. Estos efectos (excepto la obtención de experiencia) son opcionales y se pueden omitir. Las acciones de algunos personajes también pueden aplicar estos efectos sin que haya un ataque y, en esos casos, el objetivo del efecto aparecerá escrito en la carta de Capacidad.

EMPUJÓN X: el objetivo se ve obligado a moverse X hexágonos en la dirección especificada por el atacante, pero cada hexágono que se mueva debe poner al objetivo más lejos del atacante de lo que lo estaba antes. Si no hay hexágonos válidos a los que empujar el objetivo, el empujón acaba. El objetivo puede pasar a través de sus aliados al ser empujado, pero no a través de sus enemigos.

TIRÓN X: el objetivo se ve obligado a moverse X hexágonos en la dirección especificada por el atacante, pero cada hexágono que se mueva debe poner al objetivo más cerca del atacante de lo que lo estaba antes. Si no hay hexágonos válidos a los que tirar el objetivo, el tirón acaba. El objetivo puede pasar a través de sus aliados al recibir un tirón, pero no a través de sus enemigos. Tanto los efectos de empujón como los de tirón se consideran movimientos; sin embargo, no se ven afectados por el terreno impracticable.

PERFORANTE X: se ignoran hasta X puntos del escudo del objetivo para el ataque. A diferencia de otros efectos, PERFORANTE se aplica al calcular el daño del ataque en lugar de hacerlo después.

Ejemplo: si se usa una capacidad de Ataque 3 PERFORANTE 2 contra un monstruo que tiene Escudo 3, el ataque ignorará 2 de los puntos de escudo del monstruo e infligirá 2 puntos de daño (modificados por una carta de Modificador de ataque).

OBJETIVO AÑADIDO: si una figura activa este efecto con una acción de ataque, la figura puede añadir un objetivo adicional que esté dentro del alcance del ataque. Todos los efectos añadidos y estados de la acción de ataque se aplican también al nuevo objetivo, con excepción de los efectos que fuesen a añadir objetivos adicionales además del objetivo añadido original (por ejemplo, ataques de zona).

#### Estados

Algunas capacidades pueden aplicar estados a sus objetivos. Cuando se aplica un estado a una figura (excepto MALDICIÓN y BENDICIÓN), se coloca la ficha apropiada en la funda de atributos, en la sección correspondiente al número de la figura del monstruo afectado. El estado permanece hasta que se cumplan los requisitos para eliminar el efecto. Sólo puede aplicarse el mismo tipo de estado una vez a cada figura; sin embargo, se pueden volver a aplicar estados de forma que reinicien su duración.

La siguiente lista detalla estados negativos. Si una capacidad contiene el nombre de uno de estos estados, dicho estado se aplicará a todos los objetivos de la capacidad, tras haber aplicado el efecto principal de la misma. Los estados se aplican independientemente de que el ataque correspondiente inflija daño.

VENENO: si una figura queda envenenada, todos los enemigos añaden Ataque +1 a todos sus ataques que tengan como objetivo esa figura. Si se usa una capacidad de Curación sobre una figura envenenada, se retira la ficha de VENENO y la curación no tiene ningún otro efecto.

HERIDA: si una figura queda herida, sufre 1 punto de daño al comienzo de cada uno de sus turnos. Si se usa una capacidad de Curación sobre una figura herida, se retira la ficha de HERIDA y la curación sigue de forma normal. Si una figura está herida y envenenada, una capacidad de Curación eliminaría ambos estados, pero no tendría ningún otro efecto.

INMOVILIZACIÓN: si una figura queda inmovilizada, no puede utilizar ninguna capacidad de movimiento. Al final de su siguiente turno, retira la ficha de INMOVILIZACIÓN.

<!-- pág. 23 -->

DESARME: si una figura queda desarmada, no puede utilizar ninguna capacidad de ataque. Al final de su siguiente turno, retira la ficha de DESARME.

ATURDIMIENTO: si una figura queda aturdida, no puede utilizar ninguna capacidad ni usar objetos, excepto realizar un descanso largo (en el caso de los personajes). Al final de su siguiente turno, retira la ficha de ATURDIMIENTO. Los jugadores siguen debiendo jugar 2 cartas o descansar en su turno, y si un jugador juega 2 cartas estando aturdido, las acciones jugadas no se usan y las cartas se descartan sin más.

CONFUSIÓN: si una figura queda confundida, está en desventaja en todos sus ataques. Al final de su siguiente turno, retira la ficha de CONFUSIÓN.

MALDICIÓN: si una figura queda maldita, debe añadir 1 carta de MALDICIÓN a su mazo de Modificadores de ataque restante y barajarlo. Cuando se revele esta carta debido a uno de los ataques de esta figura, se retira del mazo en lugar de colocarla en la pila de descartes de Modificadores de ataque. Ten en cuenta que hay 2 mazos de maldiciones distintos: 10 cartas con [monstruo] en la esquina inferior izquierda y 10 cartas con [personaje]. Las cartas [monstruo] sólo se pueden incluir en el mazo de Modificadores de ataque de los monstruos (cuando quede maldito un monstruo), y las cartas [personaje] sólo se pueden incluir en el mazo de Modificadores de ataque de un personaje (cuando quede maldito un personaje o la invocación de un personaje). De este modo, en un mazo no pueden incluirse más de 10 cartas de maldición.

La siguiente lista detalla estados positivos. Las figuras pueden aplicar estados positivos a aliados o a sí mismas mediante determinadas acciones. Los estados positivos no pueden eliminarse antes de tiempo.

INVISIBILIDAD: si una figura es invisible, los enemigos no pueden centrar su atención en ella ni tomarla como objetivo. La invisibilidad no afecta a las interacciones de la figura con sus aliados. Al final de su siguiente turno, retira la ficha de INVISIBILIDAD. Los monstruos tratan los personajes invisibles exactamente como si fueran obstáculos.

FORTALECIMIENTO: si una figura queda fortalecida, tiene ventaja en todos sus ataques. Al final de su siguiente turno, retira la ficha de FORTALECIMIENTO.

BENDICIÓN: si una figura queda bendecida, debe añadir 1 carta de BENDICIÓN a su mazo de Modificadores de ataque restante y barajarlo. Cuando se revele esta carta mediante uno de los ataques de la figura, se retira del mazo en lugar de colocarla en la pila de descartes de Modificadores de ataque.

#### Inducciones elementales

Algunas capacidades tienen una afinidad elemental asociada (fuego, hielo, aire, tierra, luz u oscuridad). Si aparece cualquiera de estos símbolos por sí solo en la descripción de una acción (a), significa que, al realizar cualquier parte de la acción, la figura debe imbuir el campo de batalla con ese elemento. Esto se representa moviendo la ficha del elemento correspondiente a la columna “Fuerte” de la tabla de inducción elemental al final del turno en el que se usara la capacidad.

<!-- pág. 24 -->

Sin embargo, al final de cada ronda, todas las inducciones elementales menguan y se mueven una posición hacia la izquierda de la tabla, de “Fuerte” a “Menguante” o bien de “Menguante” a “Inerte”.

Las inducciones elementales se pueden usar para aumentar los efectos de algunas capacidades. Este aumento se representa mediante un símbolo elemental tapado por una [X] roja (b), seguido de dos puntos y la forma en la que aumenta la capacidad si se consume el elemento. Si se usa una capacidad que consuma un elemento y la ficha del elemento correspondiente está en la columna Fuerte o Menguante, es posible usar esa ficha de elemento para aumentar la capacidad; para ello, mueve la ficha a la columna Inerte. No puede usarse un mismo icono para consumir más de una inducción, y no es posible crear un elemento y consumirlo en el mismo turno, pero cualquiera podría consumirlo en un turno posterior del orden de iniciativa dentro de la misma ronda.

Si una capacidad contiene varios aumentos, el jugador puede elegir cuáles usa y en qué orden. Si un mismo aumento indica el uso de varios elementos, deben usarse todos los elementos para activar ese aumento.

Al igual que los personajes, los monstruos también tienen la capacidad de crear y consumir elementos. Los monstruos consumen elementos siempre que puedan, y todos los monstruos activados de ese tipo obtendrán el beneficio del elemento consumido, no sólo el primer monstruo que lo consuma.

Este círculo multicolor representa un elemento cualquiera de los seis elementos posibles. Si aparece este símbolo en la carta de Capacidad de un monstruo, los jugadores eligen qué elemento se crea o consume.

<!-- pág. 25 -->

#### Bonificaciones activas

Algunas capacidades pueden otorgar a un personaje o a sus aliados bonificaciones para otras capacidades, ya sea de forma continua hasta que se cumplan ciertas condiciones o bien durante el resto de la ronda. Estas capacidades se indican mediante símbolos, y las cartas que tienen este tipo de efectos se juegan en la zona activa, frente al jugador, para tener en cuenta estas bonificaciones.

Las bonificaciones continuas se identifican mediante el símbolo [bonificación continua] en la carta. Los efectos de estas capacidades están activos desde el momento en el que se juegue la carta hasta que se cumplan las condiciones indicadas en ella. Por lo general, estas condiciones llevan la cuenta de las veces que ha tenido lugar un suceso del juego concreto, como realizar un ataque o defenderse de uno. Coloca una ficha en la primera posición indicada de la acción de la carta y haz que avance una posición cada vez que se active el efecto, de izquierda a derecha o de arriba abajo. Cuando se haya usado la capacidad una vez por cada espacio que haya en la carta, retírala del juego y colócala en la pila de pérdida. Los jugadores deben usar los beneficios de una bonificación continua cuando sea posible hacerlo, incluso si no obtienen nada con ello. Si no se especifica ninguna condición ni hay espacios marcados, la carta permanecerá en la zona activa del jugador durante el resto del escenario y puede ser retirada del juego en cualquier momento si la colocas en la pila de pérdida.

Ejemplo: la Tejedora de hechizos juega su capacidad Armadura de escarcha, que previene las 2 próximas fuentes de daño que le inflijan. Coloca una ficha de Personaje en el primer círculo de la carta (a). A continuación, cada vez que fuese a sufrir 1 o más puntos de daño de forma normal, se aplica la bonificación, el daño es prevenido y la ficha se mueve una vez hacia delante. Cuando la ficha se mueva dos veces, la carta pasa a la pila de pérdida del jugador y la bonificación deja de estar activa.

Las bonificaciones de ronda tienen el símbolo [bonificación de ronda] en la carta. El efecto de la capacidad está activo desde el instante en el que se juegue la carta hasta el final de la ronda, en cuyo momento se coloca la carta en la pila de descartes o de pérdida del jugador (en función de si la acción contiene también un símbolo [perdida]).

Aunque una carta de bonificación pueda colocarse en la zona activa, se sigue considerando descartada o perdida, en función de si la acción contiene también un símbolo [perdida]. Estas cartas pueden moverse a la pila apropiada en cualquier momento; sin embargo, al hacerlo se eliminan inmediatamente las bonificaciones que estuviera aplicando la carta.

##### Escudo

Una capacidad de bonificación de “Escudo X” le da a su receptor una bonificación defensiva que reduce en X cualquier valor de ataque al que se enfrente. Pueden acumularse varias bonificaciones de escudo entre sí y aplicarse en cualquier orden. Las bonificaciones de escudo sólo se aplican al daño infligido por un ataque.

<!-- pág. 26 -->

##### Represalia

Una capacidad de bonificación de “Represalia X” hace que el receptor inflija X puntos de daño a figuras que la ataquen desde un hexágono adyacente por cada ataque realizado. Las bonificaciones de represalia también pueden ir acompañadas por un valor “Alcance Y”, lo que significa que el daño de represalia se le aplica a cualquier atacante que esté a Y o menos hexágonos. La represalia tiene efecto después del ataque que la activa. Si la figura que realiza la represalia muere o queda agotada por el ataque, entonces la represalia no tiene lugar. Pueden acumularse varias bonificaciones de represalia entre sí, y la represalia no es un ataque ni un efecto que tome objetivos.

#### Curación

Una capacidad de “Curación X” permite a una figura recuperar X puntos de vida o hacer que los recupere un aliado que esté dentro del alcance de la capacidad. Las curaciones siempre van acompañadas de una de las dos siguientes indicaciones:

- “Alcance Y” significa que la curación puede afectar a cualquier aliado que esté a Y o menos hexágonos de distancia o a la figura que la realiza. Al igual que todas las capacidades a distancia, el receptor debe estar dentro de la línea de visión.

- “Personal” significa que la figura sólo puede afectarse a sí misma con la curación.

#### Invocación

Algunas capacidades invocan a otras figuras aliadas en el tablero. Las figuras invocadas (invocaciones) se colocan en un hexágono vacío adyacente a la figura que realiza la invocación. Si no hay hexágonos disponibles, no puede usarse la capacidad de invocación. Las invocaciones se representan mediante fichas de Invocación de colores. Hay 8 colores distintos de fichas de Invocación, de forma que pueden seguirse varias invocaciones a la vez, y los jugadores pueden asignar cualquier color que quieran a una invocación concreta, colocando marcadores sobre sus cartas de Capacidad de invocación para saber cuál es cuál.

Las invocaciones tienen atributos básicos de puntos de vida, valor de ataque, valor de movimiento y valor de alcance, además de cualesquiera rasgos especiales que aparezcan en la carta de Capacidad. Una invocación se considera una bonificación continua (la carta se coloca en la zona activa) hasta que pierda todos sus puntos de vida, hasta que la carta de Capacidad correspondiente sea retirada de la zona activa o bien hasta que el invocador quede agotado, en cuyo momento la invocación es retirada del tablero.

El turno de una invocación dentro del orden de iniciativa siempre tiene lugar inmediatamente antes del personaje que la invocó, y va por separado respecto al turno de ese personaje. Las invocaciones no las controla el jugador que las invoca, sino que emplean las reglas automatizadas de los monstruos, siguiendo de forma permanente la carta de Capacidad “Movimiento+0, Ataque+0” (consulta [Turno de los monstruos](#turno-de-los-monstruos) (las páginas 29-32)) y empleando el mazo de Modificadores de ataque del jugador para realizar sus ataques.

Un jugador puede tener en juego varias capacidades de invocación distintas a la vez, en cuyo caso actuarán en el orden en el que hayan sido invocadas. Las figuras invocadas nunca juegan un turno en la misma ronda en la que fueron invocadas. Las bajas de una invocación se le acreditan al propietario de la misma.

<!-- pág. 27 -->

#### Recuperación y reposición

Algunas capacidades permiten a un jugador recuperar cartas de Capacidad descartadas o perdidas. Esto significa que el jugador puede mirar en su pila de descartes o de pérdida (o las cartas descartadas o perdidas que haya en su zona activa), elegir como máximo la cantidad especificada por la capacidad y devolverlas a su mano inmediatamente. Sin embargo, algunas cartas no pueden ser recuperadas ni repuestas tras perderlas, lo cual se indica con el símbolo [perdida]. Este símbolo se aplica a la carta independientemente de cómo se perdiera o consumiera.

Las capacidades de reposición permiten a los jugadores recuperar el uso de cartas de Objeto gastadas o consumidas.

Tanto en el caso de la recuperación como de la reposición, el tipo de carta obtenida (descartada o perdida en las cartas de Capacidad y gastada o consumida en las de Objeto) viene indicado en la capacidad.

No puede recuperarse ni reponerse tras perderla o consumirla

#### Saqueo

Una capacidad de “Saqueo X” permite a un personaje coger todas las fichas de Dinero y piezas de Tesoro que haya a alcance X o menos. Esta acción no se ve afectada por las posiciones de los monstruos o de los obstáculos, pero se sigue considerando una capacidad a distancia a efectos de línea de visión. Las fichas de Dinero se dejan en la reserva personal del jugador y no se comparten con el resto. Si se saquea una pieza de Tesoro, hay que consultar inmediatamente el número de referencia en el índice de tesoros que aparece al final del Libro de escenarios para determinar lo que se ha encontrado (consulta [Tesoro](#tipos-de-piezas-de-terreno) (la página 15)). Si un personaje saquea un objeto del que ya posea una copia, el objeto nuevo se vende inmediatamente a la reserva disponible de la ciudad (consulta [Comprar y vender objetos](#comprar-y-vender-objetos) (la página 43)).

##### Saqueo del final del turno

Además de las distintas capacidades de saqueo, un personaje también debe saquear todas las fichas de Dinero o piezas de Tesoro que haya en el hexágono que ocupe al final de su turno. Las invocaciones no realizan el saqueo del final del turno.

#### Obtención de experiencia

Algunas acciones tienen un valor de experiencia vinculado a ellas e indicado por [XP]. Cuando se realiza una acción así, el personaje obtiene la cantidad de experiencia especificada. No se puede jugar una carta de Capacidad sólo para obtener la experiencia; el personaje debe usar una o más de las capacidades de la carta para conseguir la experiencia. Además, a veces la acción indicará que la experiencia sólo se obtiene en determinadas condiciones, como después de consumir una inducción elemental o si el objetivo atacado está adyacente a aliados del atacante (a). Algunas bonificaciones continuas también conceden experiencia a los personajes, lo que se indica mediante [XP], cuando se gasta esa carga de la bonificación (b) (es decir, cuando la ficha de Personaje sale de ese espacio). Los personajes no obtienen experiencia automáticamente por matar monstruos. Sólo se gana experiencia usando acciones concretas.

<!-- pág. 28 -->

La experiencia se registra en el lado derecho del dial de vida y experiencia de cada jugador, girando la rueda hasta que aparezca el número apropiado (c).

#### Daño de los personajes

Siempre que se inflija daño a un personaje, el jugador tiene dos opciones:

- Sufrir el daño y reflejar su nuevo total de puntos de vida en el dial correspondiente o bien...

- Elegir 1 carta de su mano para perderla o 2 cartas de su pila de descartes para perderlas y prevenir así el daño (se siguen aplicando los posibles efectos adicionales del ataque). Ten en cuenta que, antes de que un personaje actúe en la ronda, las 2 cartas elegidas al comienzo de esta no se encuentran ni en la mano del jugador ni en las pilas de descartes o pérdida, de forma que no se pueden elegir para perderlas y prevenir el daño.

Siempre que un personaje se cure, ajusta su total de puntos de vida en el dial (d). El valor del dial no puede superar la cantidad máxima de puntos de vida que se indica en la tarjeta de personaje (e) del jugador.

#### Agotamiento

Un personaje puede quedar agotado de dos formas distintas:

- Si queda por debajo de 1 punto de vida en el dial de vida y experiencia, o bien...

- Si, al comienzo de una ronda, un jugador no puede jugar 2 cartas de su mano (porque sólo tiene 1 carta o no le queda ninguna) ni tampoco puede descansar (porque sólo tiene 1 carta o ninguna en su pila de descartes). El agotamiento debido a no tener suficientes cartas no afecta al total de puntos de vida actual del personaje.

En cualquier caso, coloca todas las cartas de Capacidad en la pila de descartes del personaje, retira su figura del tablero y el personaje deja de poder participar en el escenario de forma alguna. No es posible recuperarse de quedar agotado durante un escenario, por lo que los jugadores deberían evitarlo a toda costa. Los jugadores perderán el escenario si todos los personajes quedan agotados durante el mismo.

#### Objetos

Los personajes pueden usar objetos en cualquier momento, incluso en mitad del uso de la capacidad de una carta, siguiendo siempre las limitaciones que aparezcan impresas en la carta de Objeto. Sin embargo, si un objeto afecta a un ataque (por ejemplo, si añade una bonificación, un efecto, ventaja o desventaja), debe usarse antes de robar el modificador de ataque. Si se añade un efecto a un ataque, éste funciona exactamente igual que si estuviera impreso en la carta de Capacidad que se usa para el ataque. No hay límite a la cantidad de objetos que puede usar un personaje durante su turno o incluso durante el uso de una sola capacidad concreta. Cualquier caso en el que se apliquen los efectos de una carta de Objeto a una situación se considera un uso. Al igual que con las capacidades continuas, un objeto que tenga varios círculos de uso debe usarse cuando la situación cumpla sus condiciones.

<!-- pág. 29 -->

### Turno de los monstruos

Las decisiones de los monstruos las controla un sistema de cartas de Capacidad automatizado que rige lo que harán los monstruos en su turno del orden de iniciativa. Los monstruos no los controla ningún jugador. Todos los monstruos realizarán las acciones indicadas en su carta de Capacidad de la ronda en el orden en el que aparezcan impresas. No se moverán ni atacarán a menos que estas acciones estén en su carta.

Ten en cuenta que cada tipo de monstruo puede tener dos rangos: normal y élite. Los monstruos normales se indican con una base blanca, y los de élite con una amarilla. Cuando actúa un monstruo de élite, debes usar los atributos de la sección “Élite” de la carta de Atributos del monstruo.

#### Orden de actuación

Todos los monstruos del mismo tipo juegan turnos individuales con el mismo valor de iniciativa que aparece en su carta de Capacidad de monstruo. Los monstruos de élite del mismo tipo se activan primero, y después lo hacen los monstruos normales de ese tipo. Si en el tablero hay más de un monstruo de élite o normal de un tipo concreto, los monstruos se activan en orden numérico ascendente según el número impreso en sus figuras (a).

Ejemplo: con la disposición de la imagen de la izquierda, el monstruo de élite de la derecha [nº 2] se activará primero, y luego lo hará el otro monstruo de élite [nº 3]. A continuación, se activará el monstruo normal de arriba [nº 1], y después el de abajo [nº 4]. Aunque [nº 1] tiene un número inferior a [nº 2] y [nº 3], éstos son de élite, por lo que se activan primero.

Además de determinar el orden de las acciones, el número de la figura del monstruo (a) se corresponde con una sección de la funda de atributos del monstruo (b) que se puede usar para llevar la cuenta del daño y las fichas de Estado.

#### Atención de los monstruos

Antes de realizar cualquier acción de su carta de Capacidad, cada monstruo individual centrará su atención en un enemigo concreto, ya sea un personaje o una invocación.

- Un monstruo se centrará en la figura enemiga contra la que pueda realizar el ataque que vaya a efectuar en ese momento empleando la menor cantidad de movimiento. Para ello, busca la ruta más corta posible para ponerse dentro del alcance y línea de visión necesarios para el ataque, y se centrará en la figura a la que pueda atacar al final de esa ruta. Esa figura enemiga se considera la “más cercana”. Da igual que el monstruo no pueda ponerse al alcance para atacar con el movimiento que tenga en ese momento, siempre y cuando exista una ruta para ponerse al alcance en algún momento. Si un monstruo no tiene ningún ataque en su carta de Capacidad de la ronda, buscará en quién centrarse como si tuviera un ataque cuerpo a cuerpo. Si se da el caso de que el monstruo pueda moverse la misma cantidad de casillas para ponerse dentro del alcance y línea de visión de varias figuras enemigas (por ejemplo porque empiece su turno dentro del alcance de varios enemigos), se comprobará la proximidad a la posición actual del monstruo (es decir, el número de hexágonos de distancia sin atravesar paredes) para determinar cuál es la “más cercana”.

<!-- pág. 30 -->

- Si hay más de un enemigo que pueda considerarse el más cercano, la segunda prioridad es centrarse en el enemigo que vaya antes en el orden de iniciativa; en este caso, se centrará en las invocaciones antes que en el personaje que las invocó, incluso en la misma ronda en la que fueron invocadas. Del mismo modo, un personaje que esté realizando un descanso largo será la última opción en la que centrarse.

Ejemplo: aunque el Salvaje (a) está físicamente más cerca del monstruo [nº 1], éste realiza un ataque cuerpo a cuerpo y puede ponerse al alcance del Manitas en menos pasos (2 en lugar de 4), de forma que el monstruo se centra en el Manitas (b).

Si se da el caso de que no haya objetivos válidos en los que centrarse porque no haya hexágonos válidos desde los que pueda atacar un monstruo (por ejemplo porque estén todos bloqueados u ocupados o porque no haya una ruta libre para llegar a ellos), independientemente de la cantidad de hexágonos que pueda moverse, el monstruo no se moverá ni atacará en ese turno, pero realizará cualesquiera otras acciones de su carta de Capacidad que pueda efectuar.

#### Movimiento de los monstruos

Un monstruo puede moverse en su turno si aparece “Movimiento±X” como parte de su carta de Capacidad. Podrá moverse un número de hexágonos igual a su valor de movimiento básico (que aparece en su carta de Atributos de monstruo) modificado en +X o –X. Si un monstruo tiene un movimiento, pero después no tiene un ataque en su carta de Capacidad, empleará su movimiento para acercarse lo más posible al objetivo en el que se ha centrado (determinado como si tuviera un ataque cuerpo a cuerpo), moviéndose por la ruta más corta posible para entrar en un hexágono adyacente al enemigo en el que se ha centrado.

Si un monstruo tiene una capacidad de ataque después de su movimiento, se moverá la menor cantidad de hexágonos posible para poder atacar al enemigo en el que se ha centrado con el máximo efecto. Si se trata de un ataque cuerpo a cuerpo con un solo objetivo, simplemente se moverá hacia el hexágono adyacente más cercano al enemigo en el que se ha centrado para atacarlo. Si se trata de un ataque multiobjetivo, se moverá hacia una posición desde la que su ataque impacte contra el enemigo en el que se ha centrado y contra tantos enemigos adicionales como sea posible.

Si el monstruo realiza un ataque a distancia, sólo se moverá hacia un hexágono desde el cuál esté dentro del alcance para realizar el mejor ataque posible. El monstruo también se alejará del enemigo en el que se ha centrado hasta que pueda realizar el ataque a distancia sin estar en desventaja. En caso de tener que elegir entre dejar de estar en desventaja frente a su enemigo principal y maximizar su ataque contra objetivos secundarios, el monstruo dará prioridad a lo primero. Aunque el monstruo no pueda moverse para quedar dentro del alcance del ataque, empleará su movimiento para acercarse lo más posible al enemigo en el que se haya centrado.

Las capacidades que no sean “Ataque” de la carta de Capacidad de un monstruo no afectan a su movimiento de ninguna forma. Simplemente se moverá según las reglas anteriores y luego usará el resto de capacidades lo mejor posible.

Ejemplo: el monstruo [nº 1] puede utilizar una capacidad “Movimiento 3”. Primero se centra en el Salvaje (a), que es el enemigo más cercano. Si el monstruo tuviera un ataque a distancia, permanecería en su hexágono actual y atacaría al Salvaje. Si tuviera un ataque cuerpo a cuerpo de un solo objetivo, se movería 1 hexágono (b) para ponerse adyacente al Salvaje y atacar. Si pudiera atacar a 2 objetivos con un ataque cuerpo a cuerpo, se movería 2 hexágonos (c) para ponerse adyacente tanto al Salvaje como al Manitas. Si pudiera atacar cuerpo a cuerpo a 3 o más objetivos, se movería 3 hexágonos (d) para ponerse adyacente a todos los personajes.

<!-- pág. 31 -->

##### Interacción de los monstruos con trampas y terreno peligroso

Los monstruos que no tengan el rasgo Vuelo consideran los hexágonos negativos (trampas o terreno peligroso) como obstáculos a la hora de determinar su atención y movimiento, a menos que el movimiento a través de uno de estos hexágonos sea la única forma que tengan de poder centrar su atención en un objetivo. En este caso, usarán la ruta que pase por la menor cantidad posible de hexágonos negativos para centrar su atención en un enemigo y sufrirán las consecuencias derivadas de ello.

Ejemplo: aunque el Manitas (a) está más cerca, el monstruo [nº 1] se centrará en el Salvaje (b) con su ataque cuerpo a cuerpo porque considera las trampas como obstáculos. Si el Salvaje no estuviera allí y el único enemigo en el que el monstruo pudiera centrar su atención fuera el Manitas, se daría el único caso en el que haría eso y cruzaría las trampas para llegar a él.

Ejemplo: la Arquera [nº 1] se centrará en el Salvaje (a), ya que puede ponerse dentro del alcance necesario para atacarlo con la menor cantidad de movimiento. Si la Arquera tuviera un ataque de alcance 3 y un movimiento de 2, se movería al hexágono (b) y atacaría al enemigo en el que se ha centrado. Sin embargo, si sólo tuviera un movimiento de 1, se quedaría donde está y no atacaría. No puede moverse a la trampa (c) incluso si eso la dejaría al alcance para atacar al Salvaje, porque sigue habiendo otra ruta viable para ponerse al alcance del Salvaje aunque no pueda seguirla en este turno. Tampoco se moverá al hexágono (d) porque no se estaría situando más cerca de estar al alcance del Salvaje.

#### Ataques de los monstruos

Un monstruo atacará en su turno si aparece “Ataque±X” como parte de su carta de Capacidad. Cualquier daño infligido se calcula según su valor de ataque básico (que aparece en su carta de Atributos de monstruo) modificado en +X o –X. Los monstruos siempre atacan a los enemigos en los que han centrado su atención (consulta [Atención de los monstruos](#atención-de-los-monstruos) (las páginas 29–30)), pero si el monstruo puede atacar a varios objetivos, atacará al enemigo en el que se ha centrado y a tantos otros enemigos como sea posible con el máximo efecto. Si un monstruo puede tomar varios objetivos para una única habilidad, la atención de los demás ataques se determina siguiendo las reglas de atención normales y excluyendo a las figuras a las que ya esté atacando. Cualquier ataque que no especifique un alcance en la carta de Capacidad del monstruo debe emplear el alcance básico que aparece impreso en la carta de Atributos del monstruo.

Los ataques de los monstruos funcionan exactamente igual que los de los personajes y se modifican mediante las bonificaciones de ataque del atacante, luego con las cartas de Modificador de ataque y después con las bonificaciones de defensa del objetivo. También pueden realizarse con ventaja o estando en desventaja, de la forma explicada en las páginas 20–21.

#### Otras capacidades de los monstruos

Curación: la curación de los monstruos funciona exactamente igual que la de los personajes, como se explica en la página 26. Con una capacidad de “Curación X”, el monstruo se curará a sí mismo o a un aliado que esté dentro del alcance indicado, en función de quién haya perdido más puntos de vida.

Invocaciones: las capacidades de invocación de los monstruos colocan nuevos monstruos en el tablero que se comportan exactamente igual que los monstruos normales y actúan según las cartas de Capacidad de monstruo que se hayan jugado para su tipo de monstruo. Los monstruos invocados se colocan en un hexágono vacío adyacente al monstruo que realiza la invocación y tan cerca de un enemigo como sea posible. Si no hay hexágonos vacíos adyacentes o no hay figuras disponibles del tipo de monstruo invocado, la invocación fracasa. Los monstruos invocados nunca actúan en la ronda en la que son invocados ni sueltan fichas de Dinero cuando los matan.

<!-- pág. 32 -->

Capacidades de bonificación: las bonificaciones de las cartas de Capacidad se activan mediante acciones sólo cuando el monstruo se activa y sólo están activas hasta el final de la ronda en la que se robó la carta.

Saqueo: los monstruos no realizan el saqueo del final del turno, pero algunos monstruos tienen acciones de saqueo. En esos casos, un monstruo cogerá todas las fichas de Dinero que estén dentro del alcance indicado. Estas fichas de Dinero se pierden, y el monstruo no vuelve a soltarlas cuando muere. Los monstruos no pueden saquear piezas de Tesoro.

#### Ambigüedad

Si las reglas hacen que alguna acción de los monstruos resulte ambigua porque hay varios hexágonos válidos a los que podrían moverse, varios objetivos igualmente válidos a los que curar o atacar o varios hexágonos hacia los que un monstruo podría dar un empujón o tirón tomando como objetivo a un personaje, los jugadores deben decidir qué opción elegirá el monstruo.

#### Jefes

En ocasiones, los jugadores se encontrarán con jefes durante sus aventuras. Todos los jefes tienen su propia carta de Atributos, pero actúan empleando un mazo de cartas de Capacidad universal de “Jefe” (a). Ten en cuenta que los jefes no se consideran monstruos normales ni de élite. Los jefes realizan acciones especiales en su turno que aparecen recogidas en su carta de Atributos. En el Libro de escenarios encontrarás explicaciones para las capacidades más complicadas. Los atributos de los jefes suelen basarse en la cantidad de personajes, lo que se indica con la letra “P” en la carta de Atributos del jefe. Por último, los jefes son inmunes a determinados estados negativos. Los estados a los que son inmunes aparecen en su carta de Atributos (b). (a)

### Final de la ronda

Cuando todas las figuras han jugado un turno, la ronda termina y puede que sea necesario realizar el paso de limpieza:

- Si se robó una carta de Modificador de ataque normal “2x” [2x] o “Nulo” [nulo] de un mazo de Modificadores de ataque durante la ronda, devuelve todos los descartes de ese mazo al mazo de robo y barájalo.

- Si se robó una carta de Capacidad de monstruo con el símbolo de devolución [devolver al mazo] al principio de la ronda, devuelve a su mazo todos los descartes del tipo de monstruo correspondiente y barájalo.

- Si hay fichas de Inducción elemental en la columna Fuerte, muévelas a la columna Menguante. Si hay fichas de Inducción elemental en la columna Menguante, muévelas a la columna Inerte.

- Coloca todas las cartas de Capacidad de bonificación activas durante la ronda en la pila de descartes o de pérdida según corresponda si la acción empleada tenía un símbolo [perdida].

- Los jugadores también tienen la opción de realizar un descanso corto (consulta [Descanso](#descanso) (la página 17)) si pueden.

<!-- pág. 33 -->

#### Marcador de ronda

Es posible que algunos escenarios precisen que los jugadores lleven la cuenta de las rondas. Para ello, puedes encontrar un marcador de ronda en la parte superior de la tabla de inducción elemental. Al final de cada ronda, sólo tienes que mover un espacio la ficha del marcador (a). Ten en cuenta que la mayoría de escenarios no requieren llevar la cuenta de las rondas.

## Terminar un escenario

Todos los escenarios pueden acabar de dos formas: éxito o fracaso. Cuando se activen las condiciones de éxito o fracaso de un escenario, se termina de jugar el resto de la ronda y luego el escenario acaba.

Tanto si tienen éxito como si fracasan, los jugadores contabilizan la experiencia que han obtenido sus personajes individuales; por otra parte, contabilizan también las fichas de Dinero que han saqueado sus personajes durante el escenario y las convierten en oro. Cada ficha de Dinero saqueada vale una cantidad de oro en función del nivel del escenario, como recoge la tabla de la página 15. No se obtiene nada que no se haya saqueado durante el escenario. Para poder empezar como nuevos cualquier escenario posterior, los jugadores también recuperan todas las cartas de Capacidad perdidas

> **Figura.** Rótulos: Carta de Objetivo de batalla · Hoja de personaje.

o descartadas, reponen todas las cartas de Objeto gastadas o agotadas y restablecen el valor máximo de puntos de vida en sus diales de vida y experiencia. Los jugadores también deben revisar sus mazos de Modificadores de ataque y retirar todas las cartas de BENDICIÓN y de MALDICIÓN y otras cartas negativas que pudieran haberse añadido mediante efectos de objetos o del escenario. Este paso también debe realizarse con el mazo de Modificadores de ataque de los monstruos. Independientemente de si se completaron o no, todos los objetivos de batalla se devuelven al mazo de Objetivos de batalla y se baraja éste.

Si los jugadores completan con éxito el escenario, reciben marcas por las cartas de Objetivo de batalla que hayan completado sus personajes. Las marcas se anotan en la hoja de personaje del jugador, y cuando se completa un conjunto de 3, el personaje obtiene una pericia adicional inmediatamente (consulta [Pericias adicionales](#pericias-adicionales) (la página 44)). Aunque un personaje hubiera quedado agotado, podrá completar su objetivo de batalla, obtener las recompensas del escenario y quedarse todo el dinero y experiencia que hubiera conseguido antes de quedar agotado siempre y cuando el escenario se complete con éxito. No hay ninguna penalización por quedar agotado. Los jugadores también reciben experiencia extra por completar con éxito el escenario. Esta bonificación es igual al doble del nivel del escenario más 4 (consulta [Nivel del escenario](#nivel-del-escenario) (la página 15)).

Si los jugadores están jugando una campaña, completar con éxito un escenario también les permitirá leer el texto de ambientación de la conclusión del escenario y obtener los beneficios indicados al final (consulta [Completar un escenario](#completar-un-escenario) (la página 49)). En una campaña, el dinero y experiencia obtenidos durante un escenario serán muy importantes para mejorar las habilidades y capacidades de los personajes, por lo que deben anotarse en la hoja de personaje del jugador (b). Si el escenario no era parte de una campaña, el dinero y la experiencia pueden emplearse para medir lo bien que lo ha hecho cada personaje.

<!-- pág. 34 -->

## Reglas especiales de los escenarios

Muchos escenarios contienen reglas adicionales. A continuación, se detallan aclaraciones para algunas de las reglas especiales más comunes en los escenarios:

- Aparición: cuando aparece un monstruo, se coloca en el tablero en su ubicación de aparición o en el hexágono vacío más cercano a esa ubicación. Si aparece un monstruo al final de la ronda, empezará a activarse en la siguiente ronda. Si aparece un monstruo durante una ronda, se activa como si acabara de ser revelado (consulta [Revelar una sala](#revelar-una-sala) (la página 19)).

- Puertas bloqueadas: algunas puertas aparecen como “bloqueadas”, lo que significa que no se pueden abrir simplemente cuando un personaje se mueva a ellas. En lugar de eso, funcionan como paredes hasta que se cumplan las condiciones de apertura detalladas en el Libro de escenarios.

- Placas de presión: las placas de presión funcionan de forma similar a los pasillos en el sentido de que no afectan al movimiento de las figuras. En lugar de eso, si un personaje ocupa una placa de presión al final de un turno, puede activar un efecto especial que se detalla en el Libro de escenarios, como abrir una puerta o hacer aparecer un monstruo.

- Destruir obstáculos: cuando el Libro de escenarios indica que un obstáculo tiene puntos de vida, éste puede ser atacado y destruido para retirarlo del tablero cuando tenga menos de 1 punto de vida. Los obstáculos que tengan puntos de vida sólo pueden ser destruidos mediante daño, y no mediante ninguna otra capacidad de los personajes. Estos obstáculos se consideran enemigos a todos los efectos de las capacidades y tienen una iniciativa de 99 a la hora de determinar la atención de las invocaciones, pero son inmunes a todos los estados negativos.

- Fichas de Objetivo y de Referencia de escenario: las fichas de Objetivo (a) se usan en muchos escenarios para representar figuras aliadas o ubicaciones de botín. En el caso de las figuras aliadas, los números de las fichas deben aleatorizarse al colocarlas, y los números determinarán el orden de activación de estas. Las fichas de Referencia de (a) (b) escenario (b) se pueden colocar en las piezas de Tablero como recordatorio de ciertos casos especiales, como el lugar donde aparecen enemigos o cuándo leer las secciones numeradas del Libro de escenarios.

- Monstruos identificados: en muchas ocasiones, el objetivo de un escenario es matar a un monstruo concreto, ya sea un jefe o una variante única de un monstruo ordinario, según lo especifiquen las reglas del escenario. Estos monstruos no se consideran normales o de élite, y por lo tanto no se ven afectados por capacidades de personajes que únicamente tengan como objetivo monstruos normales o de élite.

- Ecuaciones: algunas propiedades de los escenarios, como los puntos de vida de los obstáculos o de los monstruos identificados, se determinan mediante ecuaciones que dependen del nivel del escenario y del número de personajes. En esos casos, “N” se refiere al nivel del escenario y “P” al número de personajes.

## Descripción de la campaña

Hay dos formas de jugar a Gloomhaven: el modo de campaña y el modo informal.

En el modo de campaña, los jugadores forman un grupo oficial de personajes y emprenden una serie de escenarios consecutivos a lo largo de varias sesiones de juego. Esto permite a los jugadores seguir una historia a medida que toman decisiones y exploran el camino que van creando. Sólo puede jugarse un escenario en modo de campaña si el grupo cumple todos los logros globales y de grupo que aparezcan como prerrequisitos en el Libro de escenarios. Además, tras haber completado un escenario en modo de campaña, ningún grupo puede volver a jugarlo en modo de campaña.

En el modo informal, los jugadores pueden jugar cualquier escenario revelado en el mapa del mundo independientemente de los logros o de si ya ha sido completado en modo de campaña. Los jugadores siguen pudiendo obtener experiencia y dinero, saquear piezas de Tesoro, completar objetivos de batalla y progresar en sus misiones personales, pero se ignoran todos los textos de historia o recompensas que aparezcan al final del escenario. Un grupo que esté en modo de campaña puede cambiar al modo informal para jugar un escenario que ya haya completado, pero se recomienda encarecidamente que no juegue en modo informal ningún escenario que no haya completado aún en el modo de campaña.

Las siguientes reglas se refieren únicamente al modo de campaña.

<!-- pág. 35 -->

### Mapa de campaña

El mapa de campaña se emplea para seguir el progreso global del mundo del juego. Las ubicaciones, logros y prosperidad del mapa se aplican de forma global a todos los grupos que jueguen en ese mundo.

#### El mapa incluye

- Un mapa de Gloomhaven (a) y sus alrededores (b). Los círculos numerados del mapa (c) representan escenarios que se pueden desbloquear a lo largo de la campaña. Cuando se desbloquea un escenario, se coloca su pegatina (d) correspondiente sobre el círculo numerado (consulta [Completar un escenario](#completar-un-escenario) (la página 49)). Cuando se completa un escenario desbloqueado en modo de campaña, se hace una marca en la casilla de la pegatina (e).

- Un sistema de coordenadas para el mapa (f), de forma que sea más sencillo encontrar las ubicaciones de los escenarios.

- Una zona para los logros globales (g). Cuando se desbloquea un logro global, debe colocarse su pegatina correspondiente (h) en uno de los espacios para pegatinas de esta zona (consulta [Logros](#logros) (la página 40)).

- Un marcador de prosperidad (i). Cuando la prosperidad de Gloomhaven aumenta, debe marcarse una casilla del marcador de prosperidad por cada punto que aumente, de izquierda a derecha (consulta [Prosperidad de Gloomhaven](#prosperidad-de-gloomhaven) (la página 48)). En determinados puntos del marcador, esto aumentará el nivel de prosperidad de Gloomhaven.

<!-- pág. 36 -->

### Hoja de grupo

Un grupo se forma cuando se reúnen varios jugadores para jugar. Para establecer la formación del grupo, empezarán una hoja nueva del bloc de hojas de grupo. Los logros del grupo, la reputación y la ubicación se anotarán en este bloc.

Un grupo puede seguir existiendo de escenario en escenario y de sesión de juego en sesión de juego mientras los jugadores quieran. La composición del grupo cambiará con el tiempo, especialmente a medida que los personajes se retiren y se creen otros nuevos. No pasa nada por realizar cambios en la composición del grupo, tanto en los personajes como en los jugadores. También pueden formarse nuevos grupos en cualquier momento, aunque para cualquier grupo nuevo deberían crearse personajes nuevos.

#### Una hoja de grupo incluye

- Un espacio para darle nombre al grupo (a). Todo grupo que se precie debería tener nombre. Échale imaginación.

- Un espacio para anotar la ubicación del escenario en curso del grupo (b). Esto es importante sobre todo para los escenarios que van conectados (consulta [Viaje y eventos de camino](#viaje-y-eventos-de-camino) (las páginas 41-42)).

- Un espacio para notas (c). Si tu grupo quiere anotar cualquier cosa, puede hacerlo aquí.

- Un espacio para anotar los logros de grupo (d). Siempre que un grupo obtenga un logro de grupo, debe anotarlo aquí (consulta [Logros](#logros) (la página 40)).

- Un marcador de reputación (e). Los grupos obtienen y pierden reputación con el paso del tiempo por diversos motivos, y esto se registra marcando y borrando casillas del medidor de reputación en el bloc (consulta [Reputación](#reputación) (la página 42)). A la derecha del medidor se encuentran los descuentos y penalizaciones en el precio de los objetos en función de si la reputación es alta o baja (f).

<!-- pág. 37 -->

### Hoja de personaje

Cuando se crea un nuevo personaje, el jugador debe empezar una hoja nueva en la sección del bloc de hojas de personaje correspondiente a ese personaje. A medida que los jugadores progresen en la campaña, tendrán que anotar en esta hoja de personaje la experiencia, oro, objetos, pericias y cartas de Capacidad disponibles en su mazo.

#### Una hoja de personaje incluye

- Un espacio para darle nombre al personaje (a). Todos los personajes deben tener nombre. Échale imaginación.

- Un espacio para anotar el nivel actual del personaje (b). A medida que los personajes obtengan experiencia, subirán de nivel (consulta [Subir de nivel](#subir-de-nivel) (las páginas 44-45)). La experiencia total necesaria aparece debajo de cada nivel (c).

- Espacios para anotar de forma detallada la cantidad de experiencia (d) y oro (e) que tiene el personaje

- Un espacio para anotar todos los objetos que posee un personaje (f).

- Una lista de pericias específica para la clase del personaje (g). Siempre que un personaje obtiene una pericia (consulta [Pericias adicionales](#pericias-adicionales) (la página 44)), anota en la lista cuál quiere.

- Un espacio para notas adicionales (h). Si los jugadores quieren anotar cualquier progreso en otros aspectos de su personaje, pueden hacerlo aquí. Este espacio también incluye una zona para anotar las marcas (i) obtenidas mediante objetivos de batalla.

<!-- pág. 38 -->

### Cartas de Misión personal

Al crear un personaje, éste recibe 2 cartas de Misión personal aleatorias, elige 1 para quedársela y devuelve la otra al mazo de Misiones personales. La misión personal de un jugador es su motivo principal para formar parte de un grupo.

#### Una carta de Misión personal incluye

- Una descripción temática de la misión (a).

- Los requisitos para completar la misión y las recompensas por hacerlo (b). Al completar una misión personal, el personaje se retirará (consulta [Anunciar la retirada de un personaje](#anunciar-la-retirada-de-un-personaje) (la página 48).

### Cartas de Diseño de objeto

Siempre que aparezca un “Diseño de objeto” como recompensa por saquear una pieza de Tesoro, el jugador que la ha saqueado debe robar 1 carta del mazo de Diseños de objetos. Estas cartas son muy parecidas a las cartas de Objeto normales, pero tienen un dorso azul, como se muestra en la imagen de la derecha. Cuando se roba una de estas cartas, el jugador debe buscar en el mazo de objetos no disponibles la otra copia del objeto robado con el mismo número de referencia y, a continuación, añade ambas cartas a la reserva de objetos disponibles de la ciudad. Es posible agotar el mazo de Diseños de objetos; si ocurre esto, las recompensas de diseños de objetos que se obtengan a partir de ese momento no tienen ningún efecto.

### Cartas de Escenario secundario aleatorio

Siempre que aparezca un “Escenario secundario aleatorio” como recompensa por saquear una pieza de Tesoro, el jugador que la ha saqueado debe robar 1 carta del mazo de Escenarios secundarios aleatorios. El escenario robado queda desbloqueado inmediatamente, por lo que debe colocarse su pegatina correspondiente en el mapa de campaña. Retira de la partida la carta del escenario robado. Es posible agotar el mazo de Escenarios secundarios aleatorios; si ocurre esto, las recompensas de escenarios secundarios aleatorios que aparezcan a partir de ese momento no tienen ningún efecto.

<!-- pág. 39 -->

### Cartas de Evento de camino y de ciudad

Los jugadores tendrán muchas oportunidades de toparse con eventos de camino y de ciudad a lo largo de una campaña. Cuando los jugadores se encuentren con un evento, deben robar la primera carta del mazo correspondiente y leer su anverso (a). Ten en cuenta que las cartas de Evento tienen contenido en ambos lados, y que el dorso (b) no debe leerse hasta haber resuelto el anverso. Los eventos de ciudad y los eventos de camino tienen un diseño y contenido distintos, pero funcionan del mismo modo. (a) (b)

#### Una carta de Evento contiene

- Una introducción temática al evento (c). Es lo primero que hay que leer.

- Un punto de decisión (d). El grupo debe ponerse de acuerdo acerca de cuál de las dos opciones quiere elegir. Tras haber tomado una decisión colectiva, se le da la vuelta a la carta y se resuelve el resultado apropiado del dorso.

- El número del evento (e). El juego hará referencia a este número cuando se les indique a los jugadores que añadan eventos concretos a sus mazos respectivos.

- Descripciones de ambas elecciones (f). Los jugadores deben leer la elección correspondiente en función de la opción que eligiera el grupo e ignorar la otra.

- El resultado de la elección (g), que está formado por un bloque de texto temático seguido de los efectos de juego que se aplican a la partida, escritos en negrita. Una elección puede tener varios resultados distintos, algunos de los cuales dependerán de condiciones concretas (consulta [Completar eventos de camino](#completar-eventos-de-camino) (las páginas 41-42)).

- Carta de Evento de camino

Iconos que indican a los jugadores que retiren de la partida la carta de Evento (h) o que la devuelvan a la parte inferior del mazo de Eventos correspondiente (i) después de resolver el resultado.

Al abrir la caja del juego y comenzar la campaña, es necesario crear un mazo de Eventos de ciudad y un mazo de Eventos de camino con los respectivos eventos de ciudad y de camino de 01 al 30 y barajarlos. Los jugadores tendrán que añadir o retirar eventos concretos de cada mazo a lo largo de la campaña. Cuando se añade una carta a un mazo de Eventos, es necesario barajarlo después. Ten en cuenta que añadir una carta a un mazo de Eventos es distinto a devolver una carta jugada a su mazo, en cuyo caso la carta simplemente se coloca en la parte inferior del mazo, sin barajar éste.

<!-- pág. 40 -->

### Cajas y sobres cerrados

La caja del juego incluye varias cajas y sobres cerrados y marcados por un símbolo o letra. En determinados momentos, el juego indicará a los jugadores que abran uno de estos sobres o cajas. Si contiene materiales para una nueva clase de personaje, ésta estará disponible para cualquiera que empiece un nuevo personaje. Si el sobre contiene otros contenidos, éstos indicarán a los jugadores cómo usarlos.

Los jugadores recibirán instrucciones para abrir cajas o sobres cuando completen misiones personales o cumplan ciertas condiciones. Estas condiciones se detallan en la página 49.

### Anales de la ciudad

La caja del juego también incluye un libro cerrado con un adhesivo llamado “Anales de la ciudad”. Los jugadores tendrán que abrir este libro cuando se retire el primer personaje, en cuyo momento pueden empezar a leer el libro de forma normal. En ciertos pasajes del libro, se indicará a los jugadores que dejen de leer hasta que se cumplan ciertas condiciones.

### Logros

El sistema de logros es la forma principal que tienen los jugadores de seguir los cambios más importantes que se produzcan en el juego y los escenarios a los que tiene acceso un grupo concreto en el modo de campaña. Hay dos tipos de logros: logros globales y logros de grupo.

Los logros globales afectan a todo el mundo del juego, independientemente de qué grupo esté jugando en él. Los logros globales se registran mediante pegatinas que se colocan en la parte superior del mapa del mundo (a). Algunos logros globales tienen un tipo concreto (indicado a continuación del logro con el formato “Tipo: Logro”; por ejemplo, “Gobierno de la ciudad: Militarista”). Sólo puede estar activo 1 logro global de cada tipo a la vez. Si se obtiene un logro global y ya hay un logro activo del mismo tipo, se sobrescribe el anterior y se coloca la pegatina nueva sobre la antigua. Es posible que haya varias copias de un mismo logro global siempre que no tengan un tipo concreto.

Los logros de grupo están vinculados a un grupo concreto y se usan principalmente para seguir qué escenarios tiene disponibles ese grupo para jugar en el modo de campaña.

<!-- pág. 41 -->

## Jugar una campaña

### Viaje y eventos de camino

Después de cada escenario, independientemente de que acabara en éxito o fracaso, los jugadores tienen la opción de regresar a Gloomhaven o de viajar inmediatamente a un nuevo escenario.

En el caso de que los jugadores viajen inmediatamente a un nuevo escenario, deben completar un evento de camino antes de empezar el nuevo escenario a menos que jueguen el mismo escenario, que el nuevo escenario esté conectado al anterior o que estén jugando en modo informal. En el Libro de escenarios, aquellos escenarios conectados a otro concreto aparecen en la parte superior derecha de la página de ese escenario (a). Si los dos escenarios están conectados, los jugadores pueden empezar inmediatamente el nuevo escenario sin completar un evento de camino.

Si los jugadores regresan a Gloomhaven, cuando hayan acabado sus asuntos en la ciudad (consulta [Visitar Gloomhaven](#visitar-gloomhaven) (las páginas 42-48)), tendrán que viajar a un nuevo escenario y completar un evento de camino a menos que el nuevo escenario esté conectado a Gloomhaven o se esté jugando en modo informal. Esta conexión también aparecerá indicada en la página o páginas del Libro de escenarios correspondientes a ese escenario.

Ejemplo: tras completar el escenario El Túmulo Negro, el grupo desbloquea el escenario Guarida del Túmulo. Estos dos escenarios están conectados, así que pueden viajar a la Guarida del Túmulo sin completar un evento de camino. En vez de eso, deciden volver a Gloomhaven para gastar el dinero que han conseguido. En ese caso, cuando viajen a la Guarida del Túmulo, tendrán que completar un evento de viaje, ya que la Guarida del Túmulo no está conectada a Gloomhaven.

#### Completar eventos de camino

Para completar un evento de camino, los jugadores roban 1 carta del mazo de Eventos de camino y leen el texto de presentación del anverso. Después de este texto, se ofrecen 2 opciones, y los jugadores deben ponerse de acuerdo para del anverso. Después de este elegir una antes de darle la vuelta a respuesta: la carta y leer el resultado correspondiente. Cuando hayan leído el resultado, no es posible cambiar la opción elegida, y los jugadores tendrán que obtener o perder aquello que indique el resultado. En función de la composición y reputación del grupo, una misma elección (A o B) puede tener varios resultados distintos. Las elecciones se leen de arriba abajo, resolviendo todos los resultados que se le apliquen al grupo.

Un resultado puede ir precedido de una de las siguientes condiciones:

- Un icono de clase. Si uno de los iconos de clase indicados coincide con el icono de clase de un miembro actual del grupo, el resultado se aplica.

- Un rango de reputación. Si la reputación del grupo se encuentra dentro del rango indicado, el resultado se aplica.

- Una cantidad de oro colectiva. Si el grupo tiene en conjunto esa misma cantidad de oro o más, pierde esa cantidad y el resultado se aplica.

- La expresión “de otro modo”. Si no se ha aplicado dos anteriores, aplica este resultado en su lugar.

Si el resultado no tiene ninguna condición es que siempre se aplica.

<!-- pág. 42 -->

Las recompensas o penalizaciones “colectivas” se distribuyen entre el grupo, mientras que las recompensas o penalizaciones que incluyen la palabra “cada” se aplican a cada personaje del grupo de forma individual. Si un jugador debe perder algo (dinero, marcas, etc.), pero no puede hacerlo porque no tiene suficiente cantidad de ese elemento para perder, perderá todo lo que pueda y seguirá resolviendo el evento. Un personaje nunca puede perder una marca que le haga perder una pericia, tener dinero negativo o caer por debajo del umbral de experiencia mínimo necesario para su nivel actual, y la ciudad nunca puede bajar de la cantidad de prosperidad mínima para su nivel actual.

#### Reputación

La reputación está vinculada a un grupo concreto y se anota en la hoja de grupo. En cualquier momento en el que se forme un grupo nuevo, éste empieza con una reputación de 0. El grupo puede obtener o perder reputación por las consecuencias de los eventos o al completar determinados escenarios. Un grupo puede tener una reputación máxima de 20 y una reputación mínima de –20.

La reputación de un grupo tiene distintas implicaciones:

- Muchos eventos tienen consecuencias que sólo se aplican si el grupo cumple unos requisitos de reputación concretos.

- Al comprar objetos, los jugadores modifican el coste en función de su reputación. Con una reputación alta, recibirán reducciones del coste, y con una reputación baja, el coste aumentará. Estas modificaciones del coste se indican en la hoja de grupo, junto al medidor de reputación.

- Algunos sobres cerrados se abren cuando un grupo alcanza determinados valores positivos o negativos de reputación.

### Visitar Gloomhaven

Siempre que un grupo vuelva a Gloomhaven, puede realizar distintas actividades: crear nuevos personajes, completar eventos de ciudad, comprar y vender objetos, subir de nivel sus personajes, donar al Santuario, mejorar cartas de Capacidad y anunciar la retirada de un personaje. Se puede activar una nueva visita a Gloomhaven después de cada escenario jugado en modo de campaña.

#### Crear nuevos personajes

El primer paso de la historia de cualquier personaje es su creación. Los jugadores crearán nuevos personajes cuando empiecen a jugar al juego por primera vez, cuando retiren a un personaje y quieran seguir jugando o simplemente en cualquier otro momento en el que quieran probar algo nuevo. La primera vez que abras la caja del juego, tendrás disponibles las siguientes 6 clases: Salvaje [clase], Manitas [clase], Tejedora de hechizos [clase], Pícara [clase], Corazón hueco y Ladrona mental [clase].

Cuando un jugador crea un personaje nuevo, puede acceder a la tarjeta de personaje de ese personaje y a su mazo de cartas de Capacidad de nivel 1 y “X”. El jugador debe empezar una hoja nueva de la clase correspondiente en el bloc de hojas de personaje, y también robará 2 cartas de Misión personal aleatorias, de las cuales elegirá 1 para quedarse y otra para devolver al mazo.

Los jugadores pueden empezar un personaje que tenga cualquier nivel igual o menor que el nivel de prosperidad de la ciudad (consulta [Prosperidad de Gloomhaven](#prosperidad-de-gloomhaven) (la página 48)). Si un jugador empieza un personaje por encima del nivel 1, debe realizar de forma consecutiva todos los pasos detallados en la página 44 por cada aumento de nivel, hasta llegar al nivel inicial que ha elegido, incluido éste. Además, un personaje recién creado recibe una cantidad de oro igual a 15 x (N+1), donde N es su nivel inicial. Los personajes empiezan con una cantidad de experiencia igual al mínimo necesario para su nivel (el número aparece bajo el nivel en la hoja de personaje).

<!-- pág. 43 -->

#### Completar eventos de ciudad

Un grupo puede completar un evento de ciudad una vez por cada visita a Gloomhaven. Los eventos de ciudad funcionan igual que los eventos de camino, pero se roban del mazo de Eventos de ciudad y suelen tener resultados más positivos que los eventos de camino.

#### Comprar y vender objetos

Cuando están en Gloomhaven, los personajes tienen la oportunidad de comprar cartas de Objeto gastando el oro que han obtenido en los escenarios. Además, los jugadores también pueden vender cualquier objeto por la mitad del precio indicado en la carta de Objeto (redondeando hacia abajo). Cuando se vende un objeto, vuelve a la reserva disponible en la ciudad y el personaje recibe la cantidad de oro apropiada. Los jugadores pueden poseer tantos objetos como puedan permitirse, pero tienen un límite a los que pueden equiparse (consulta [Cartas de Objeto](#cartas-de-objeto) (la página 8)). Los jugadores no pueden intercambiar dinero ni objetos.

Al abrir la caja del juego y comenzar la campaña, la reserva disponible en la ciudad está compuesta de todas las copias de los objetos 001 a 014. A lo largo de la campaña, se añadirán muchos objetos más a la reserva disponible de la

ciudad en función de estas condiciones:

- En cualquier momento que se obtenga un diseño de objeto en un escenario o evento, se añadirán a la reserva disponible de la ciudad todas las copias de esa carta de Objeto.

- A medida que la ciudad obtenga niveles de prosperidad (consulta [Prosperidad de Gloomhaven](#prosperidad-de-gloomhaven) (la página 48)), habrá nuevos objetos disponibles en la reserva. La lista de los objetos que pasan a estar disponibles en cada nivel de prosperidad aparece en la tabla de la derecha.

- Por último, cuando un personaje se retira, todas sus cartas de Objeto vuelven a la reserva de la tienda.

En cualquier grupo, la cantidad de objetos disponible para su compra está limitada por la cantidad existente de copias de la carta de Objeto. Ningún personaje puede poseer duplicados de un mismo objeto. Si un grupo distinto juega al juego con otros personajes, los objetos que poseen los personajes que no se usen se consideran en la reserva disponible en la ciudad y se pueden comprar. Los jugadores siempre deben anotar qué objetos poseen en sus hojas de personaje para evitar problemas si distintos grupos juegan con las mismas cartas.

<!-- pág. 44 -->

#### Subir de nivel

Cuando un personaje obtiene la cantidad de experiencia indicada en la tabla de la derecha, debe subir de nivel. Las subidas de nivel sólo se producen en la ciudad.

Cuando un personaje alcanza un nuevo nivel, añade 1 carta nueva a su reserva de cartas activas. La carta elegida debe ser de la clase del personaje y tener un nivel de carta igual o menor que el nuevo nivel del personaje.

Además, al subir de nivel, el jugador debe marcar 1 de las casillas de pericia de la parte derecha de su hoja de personaje. Esto supone una evolución del mazo de Modificadores de ataque del personaje. Aplica al mazo de Modificadores del personaje las bonificaciones de la pericia marcada empleando el mazo de cartas de Modificador disponibles para su clase. Si una pericia tiene varias casillas junto a ella, esto quiere decir que la pericia se puede obtener varias veces pagando el coste de una pericia cada vez.

Ejemplo: el Salvaje marca la pericia “Sustituye 1 carta [−1] por 1 carta [+1]”, así que retira 1 carta [−1] de su mazo de Modificadores de ataque y añade 1 carta [+1] (cogiéndola del mazo de Modificadores del Salvaje) en su lugar.

Por último, subir de nivel también aumenta el total de puntos de vida del personaje (a), como se indica en su tarjeta de personaje. Subir de nivel nunca cambia el tamaño de mano máximo del personaje, que es fijo para cada clase.

##### Pericias adicionales

Cada vez que un personaje complete con éxito una carta de

Objetivo de batalla al final de un escenario, recibe una cantidad de marcas que se anotan en la zona apropiada de su hoja de personaje. Por cada 3 marcas que obtenga un personaje, recibirá inmediatamente una pericia adicional en su hoja de personaje y aplicará su efecto en su mazo de Modificadores de ataque. Cualquier marca obtenida por objetivos de batalla que sobre tras lograr una pericia se acumula para la siguiente pericia. Un mismo personaje puede conseguir hasta 6 pericias adicionales de este modo.

<!-- pág. 45 -->

##### Crear una mano de cartas

Al jugar una clase por primera vez, se recomienda que los jugadores empleen una mano formada únicamente por cartas de nivel 1 (indicadas mediante [nivel 1] bajo el nombre). Sin embargo, todos los personajes también tienen acceso a 3 cartas [nivel X]. Por lo general, se trata de cartas más complejas que las de nivel 1 y adecuadas para situaciones muy concretas. Cuando un jugador esté familiarizado con las capacidades básicas de su clase, puede plantearse añadir 1 o más cartas [nivel X] a su mano, retirando esa misma cantidad de cartas de nivel 1 para cumplir el límite de mano.

A medida que los personajes suben de nivel, tienen disponibles cartas de Capacidad de niveles superiores. Aunque tengan acceso a más cartas, la cantidad máxima de cartas que pueden llevar en combate (el límite de mano) sigue siendo la misma. Por lo tanto, al comienzo de un escenario, los jugadores deben elegir una cantidad de cartas igual al límite de mano del personaje de entre la reserva de cartas disponibles del personaje. Estas cartas formarán la mano del personaje y serán las únicas que podrá usar durante el escenario.

##### Adaptación de los escenarios

A medida que los personajes suban de nivel, el nivel de escenario recomendado también aumentará, como se explica en la página 15. Esto aumentará los niveles de los monstruos, el daño de las trampas, el oro obtenido por las fichas de Dinero y la experiencia por completar el escenario.

#### Donar al Santuario

Una vez por cada visita a Gloomhaven, cada personaje puede donar 10 de oro al Santuario del Gran Roble, un templo y hospital de la ciudad. Al hacerlo, el personaje que hace la donación añade 2 cartas de Modificador de ataque de BENDICIÓN [bendición] a su mazo de Modificadores de ataque para el siguiente escenario.

#### Mejorar cartas de Capacidad

Cuando los jugadores hayan completado el logro global “El poder de la mejora”, pueden gastar oro al visitar Gloomhaven para aumentar el poder de sus cartas de Capacidad. Para ello, el jugador coloca la pegatina que quiera de la hoja de mejora sobre el lugar indicado (a) de una carta de Capacidad que tenga en la reserva de cartas activas de su personaje. Esta pegatina marca una mejora permanente de la capacidad.

Las cartas de Capacidad se pueden mejorar de diversas formas, y cada una cuesta una cantidad de oro concreta. Este coste debe pagarlo el personaje cuya carta de Capacidad se quiera potenciar.

<!-- pág. 46 -->

Cada tipo de pegatina de mejora tiene una función distinta y restricciones respecto al lugar en el que puede colocarse. La expresión “Línea principal de capacidad” se refiere a la capacidad escrita en fuente más grande (en comparación con los modificadores escritos en fuente más pequeña bajo la línea principal):

Se puede colocar en cualquier línea de capacidad o línea de atributo básico de invocación que tenga un valor numérico. Ese valor aumenta en 1.

Se puede colocar sobre cualquier línea principal de capacidad que tenga como objetivo a enemigos. El estado especificado se aplica a todos los objetivos de la capacidad.

Se puede colocar sobre cualquier línea principal de capacidad que afecte a aliados o a ti mismo. Una capacidad “Movimiento” no cuenta como que te afecte a ti mismo. El estado especificado se aplica a todos los objetivos de la capacidad.

Se puede colocar sobre cualquier línea de capacidad “Movimiento”. El movimiento ahora se considera un salto.

Se puede colocar sobre cualquier línea principal de capacidad. El elemento se crea cuando se usa la capacidad. En el caso de [cualquier elemento], el jugador elige el elemento de forma normal.

Se puede colocar para aumentar la representación gráfica de un ataque de zona. El nuevo hexágono se convierte en un objetivo adicional del ataque.

El coste básico asociado con cualquier mejora depende de la pegatina y de la capacidad que vaya a mejorar ésta. Si una mejora se aplica a una capacidad que tenga varias figuras como objetivo, dobla su coste básico (excepto cuando estés calculando el coste de un hexágono de ataque). Se añadirán costes adicionales según el nivel de la carta de Capacidad y la cantidad de pegatinas de mejora que se hayan colocado ya en la misma acción.

La cantidad total de cartas mejoradas que puede haber en el mazo de Capacidades de una clase debe ser igual o menor que el nivel de prosperidad de la ciudad. Una vez colocadas, las pegatinas de mejora nunca pueden quitarse. Las mejoras se mantienen durante todas las encarnaciones de una clase de personaje, incluso tras la retirada de un personaje.

<!-- pág. 47 -->

200 o, divididos por el número de hexágonos que tenga como objetivo el ataque en ese momento

Ejemplo: el Salvaje quiere mejorar la primera acción de su carta de Capacidad con un +1 al ataque (a). El coste básico para hacerlo es 50 de oro, pero se dobla porque el objetivo tiene objetivos múltiples. Además, se trata de una carta de Capacidad de nivel 3 (b), así que se suman otros 50 de oro para un total de 150 de oro. A continuación, el Salvaje quiere añadir un hexágono de ataque adicional a la acción (c). Esto normalmente costaría 66 de oro (200 de oro dividido entre los 3 hexágonos existentes y redondeado hacia abajo), pero vuelven a sumarse 50 de oro porque la carta es de nivel 3, y ahora también se suman 75 de oro porque la acción ya tiene una mejora anterior, lo que da un total de 191 de oro.

<!-- pág. 48 -->

#### Anunciar la retirada de un personaje

Si un personaje cumple los requisitos de su misión personal y está visitando Gloomhaven, debe anunciar su retirada. El personaje puede realizar cualesquiera otras actividades de la ciudad antes de hacerlo, pero no puede jugar ningún escenario nuevo si su misión personal se ha completado. El personaje ha cumplido sus sueños y no tiene motivación alguna para seguir explorando ruinas repletas de monstruos. Todos los materiales del personaje deben devolverse a la caja, los objetos que poseyera se devuelven a la reserva disponible de la ciudad y todo el dinero que poseía el personaje se pierde. Además, la ciudad obtiene 1 punto de prosperidad.

Completar misiones personales siempre desbloquea nuevo contenido para el juego. Permite que el jugador abra una caja o un sobre cerrado, lo que generalmente desbloquea una nueva clase de personaje. En cualquier momento en el que los personajes deban abrir una caja o sobre que ya haya sido abierto anteriormente por cualquier motivo, en lugar de eso se desbloquean 1 diseño de objeto y 1 escenario secundario aleatorio nuevos (consulta la página 38 para ver más detalles). Cuando se completa una misión personal, su carta de Misión personal se retira de la partida.

Cada vez que un jugador individual retira un personaje, dicho jugador también obtiene 1 pericia extra que podrá aplicar a cualquier personaje que cree en el futuro. Este efecto es acumulativo, por lo que cuando un jugador retire su segundo personaje, su siguiente personaje obtendría 2 pericias adicionales. Aunque este efecto se aplica por jugador, si un mismo jugador controla varios personajes a la vez en una campaña (por ejemplo, al jugar en solitario), considera el legado de cada personaje que controle como un jugador distinto a efectos de esta bonificación.

Cuando una clase de personaje concreta se retira por primera vez, suelen añadirse nuevos eventos de camino y de ciudad a los mazos de Eventos. El número de referencia de estos eventos aparece en el dorso de la tarjeta de personaje de esa clase, en la parte inferior derecha (el número que está a la derecha de la barra). Además, siempre que se desbloquee una nueva clase de personaje mediante una retirada o cualquier otro medio, también se añaden nuevos eventos de camino y de ciudad a los mazos. Este número de referencia se encuentra en el dorso de la tarjeta de personaje de la clase desbloqueada, en la parte inferior derecha (el número que está a la izquierda de la barra). Cada número de referencia se aplica tanto al mazo de Eventos de ciudad como al mazo de Eventos de camino.

Cuando el personaje de un jugador se retira, puede elegir un nuevo personaje con el que jugar y roba 2 nuevas cartas de Misión personal, de las que se quedará 1 y descartará la otra. Los jugadores son libres de emplear la misma clase para su nuevo personaje, pero puesto que completar misiones personales suele desbloquear una clase nueva, esto debería animar a los jugadores a explorar nuevos estilos de juego a lo largo de la campaña. Los personajes nuevos pueden empezar en cualquier nivel que sea igual o menor que el nivel de prosperidad de la ciudad en ese momento.

Es posible quedarse sin cartas de Misión personal. Si no quedan cartas de Misión personal cuando un personaje cree un nuevo personaje, éste no recibirá una misión personal. Un personaje que no tenga misión personal no puede retirarse nunca, pero el jugador tiene plena libertad para cambiar de personaje siempre que quiera.

#### Prosperidad de Gloomhaven

A medida que los personajes se vuelvan más poderosos, la ciudad de Gloomhaven crecerá en prosperidad. Se puede obtener prosperidad de Gloomhaven mediante determinados eventos o completando determinados escenarios. Los puntos de prosperidad se marcan en la parte inferior del mapa (a), y la ciudad alcanza nuevos niveles al llegar a los umbrales designados.

Cuando la ciudad alcanza un nuevo nivel de prosperidad, los jugadores obtienen 2 beneficios:

- Hay disponibles nuevos objetos para su compra según la tabla de la página 43.

- Los nuevos personajes pueden empezar en cualquier nivel que sea igual o menor que el nivel de prosperidad de la ciudad. Del mismo modo, cualquier personaje que tenga un nivel inferior al nivel de prosperidad puede subir de nivel inmediatamente para igualarlo. En cualquier caso, debes seguir los pasos para subir de nivel de la página 44, fijando el valor de experiencia del personaje en el valor mínimo necesario para el nuevo nivel.

<!-- pág. 49 -->

### Completar un escenario

Cuando se completa con éxito un escenario como parte de la campaña, el grupo obtiene una serie de recompensas que se detallan al final de su entrada del Libro de escenarios. Las recompensas

pueden incluir logros globales o de grupo, oro o experiencia extra para cada miembro del grupo, aumentos de prosperidad, escenarios desbloqueados, objetos o diseños de objetos. Como se explica en la página 42, si una recompensa de un escenario indica que el grupo debe perder algo, no puede perder más cantidad de la que tenga de ese elemento.

Cuando se desbloquee un nuevo escenario, busca u número correspondiente en el mapa del mundo mediante las coordenadas y coloca la etiqueta del escenario sobre él (a). Ten en cuenta que los números de escenario rodeados por un círculo que aparecen en los textos de historia no desbloquean escenarios. Son meras referencias acerca de no desbloquean lo que cuenta el texto de historia. Si se obtiene un objeto como recompensa, los jugadores deben buscar 1 copia de dicho objeto en el mazo de objetos no disponibles y dársela a uno de los personajes presentes. Si se obtiene un diseño de objeto como recompensa, los jugadores deben buscar todas las copias de ese objeto en el mazo de objetos no disponibles y añadirlas a la reserva de objetos disponibles de la ciudad junto con la carta de Diseño en sí.

## Condiciones especiales para abrir sobres

Obtén 5 logros globales “Tecnología antigua”: abre el sobre

Haz que un grupo obtenga los logros de grupo “La orden del draco” y “El tesoro del draco”: añade el evento de ciudad 75 y el evento de camino 66 a los mazos y obtén el logro global “El draco auxiliado”

Dona un total de 100 de oro al Santuario del Gran Roble: abre el sobre

Ten una reputación de grupo de 10 o más: abre la caja

Ten una reputación de grupo de 20: añade el evento de ciudad 76 y el evento de camino 67 a los mazos

Ten una reputación de grupo de –10 o menos: abre la caja

Ten una reputación de grupo de –20: añade el evento de ciudad 77 y el evento de camino 68 a los mazos

Retira un personaje: abre el Libro de anales de la ciudad

## Variante de juego: aleatoriedad reducida

Si los jugadores quieren reducir las diferencias de daño que provocan los efectos de los modificadores de ataque “2x” y “Nulo” [nulo], pueden considerar la BENDICIÓN [bendición] y las cartas “2x” normales como modificadores +2 [+2], y la MALDICIÓN [maldición] y las cartas “Nulo” normales como modificadores –2 [−2]. En estos casos, los jugadores siguen teniendo que barajar el mazo de Modificadores de ataque correspondiente al final de una ronda en la que se haya robado una de estas cartas.

<!-- pág. 50 -->

## Variante de juego: muerte permanente

Si los jugadores quieren que la amenaza de los peligros sea mayor, pueden decidir jugar a Gloomhaven con muerte permanente. Cualquier personaje morirá de forma permanente cuando tenga menos de 1 punto de vida (en lugar de quedar agotado). Los personajes pueden seguir quedando agotados de forma normal si no pueden descansar ni jugar cartas, con la diferencia de que su figura permanecerá en el tablero y podrá seguir siendo objetivo de ataques de monstruos. El personaje no puede actuar de modo alguno y se considera que tiene una iniciativa de 99 a efectos de la atención de los monstruos. Después de fracasar en un escenario, cualquier personaje que siga con vida al final de la ronda sobrevivirá y podrá seguir jugando.

Cuando un personaje muere, todos los materiales del personaje deben devolverse a la caja, los objetos que poseyera se devuelven a la reserva disponible de la ciudad y todo el dinero que poseía el personaje se pierde. Su misión personal se devuelve al mazo de Misiones personales (que se baraja) y su hoja de personaje se retira de la partida. Para seguir jugando, el jugador cuyo personaje ha muerto debe crear un nuevo personaje (consulta [Crear nuevos personajes](#crear-nuevos-personajes) (la página 42)).

## Variante de juego: mazo de Mazmorras aleatorias

En lugar de jugar un escenario del Libro de escenarios, los jugadores siempre tienen la opción de explorar una mazmorra aleatoria. Las mazmorras aleatorias no hacen progresar la campaña en modo alguno, pero se pueden emplear para obtener experiencia, dinero o marcas adicionales y para progresar en las misiones personales de los personajes.

Cada mazmorra aleatoria está formada por 3 salas generadas al azar, y el objetivo siempre es despejar de monstruos todas las salas. Las 3 salas se prepararán de una a una, y sólo se revela la siguiente sala cuando se haya abierto la puerta que lleva a ella. Cada sala se prepara usando 1 carta de Sala y 1 carta de Monstruo que se robarán al azar de la parte superior de sus mazos tras barajarlos.

### Una carta de sala incluye

- Un nombre en forma de sustantivo (a). Al combinarlo con el nombre en forma de adjetivo de la carta de Monstruo, formará el nombre completo de la sala.

- Una representación gráfica de la pieza o piezas de Tablero empleadas en la preparación de la sala, junto con 12 indicaciones numéricas para saber dónde colocar los distintos elementos de la carta de Monstruo durante la preparación (b). La preparación de la sala también mostrará cualesquiera piezas de Terreno de obstáculo que haya que colocar. Es posible quedarse sin un tipo concreto de piezas de Terreno al preparar la segunda o tercera salas. En ese caso, usa una pieza de Terreno comparable del mismo tipo.

- Indicaciones de por dónde entran (c) los jugadores a la sala o por dónde salen (d) y de los tipos de entradas y salidas que hay (consulta más adelante para ver más detalles). Las entradas y salidas siempre se corresponden con el medio hexágono más cercano a la conexión de la pieza. Si se trata de la primera sala de la mazmorra, los jugadores pueden colocar sus figuras en cualquier hexágono vacío que esté a 2 o menos hexágonos de la entrada. Si la primera sala tiene varias entradas, los jugadores pueden ponerse de acuerdo para elegir en qué entrada van a empezar.

- El tipo de entrada disponible para la sala en el dorso de la carta (e). Hay 2 tipos de entradas y salidas: A y B. Si los jugadores salen de <!-- pág. 51 --> una sala por una salida A, deben entrar en la siguiente sala por una entrada A, y lo mismo en el caso de la B. Si la entrada de la primera sala del mazo no se corresponde con la salida que emplearon los jugadores en la sala anterior, descarta la primera carta hasta que aparezca una con un tipo de entrada apropiado.

Si una sala tiene 2 salidas, los jugadores pueden usar la que quieran, aunque la que no usen quedará clausurada. Si una sala tiene 2 entradas, los jugadores deben usar la correspondiente a la salida de la sala anterior.

- Penalizaciones por revelar la sala (f). Siempre que se revele y prepare una nueva sala, puede activarse una penalización en función de la sala y de la dificultad escogida por los jugadores. La dificultad sugerida es no usar penalizaciones en la primera sala, la penalización leve de la segunda sala cuando sea revelada y la penalización grave de la tercera sala cuando sea revelada. Los jugadores pueden aumentar o disminuir la cantidad y severidad de las penalizaciones como deseen, hasta el punto máximo de activar penalizaciones graves para cada una de las tres salas cuando sean reveladas. Si se hace referencia al personaje que abrió la puerta en la penalización de la primera sala, los jugadores pueden decidir quién será el objetivo de la penalización. Si se hace referencia a la sala anterior en la penalización de la primera sala, no ocurre nada.

- La pieza o piezas que se usan para crear la sala (g).

#### Una carta de monstruo incluye

- Un nombre en forma de adjetivo (h). Al combinarlo con el nombre en forma de sustantivo de la carta de Sala, formará el nombre completo de la sala (por ejemplo, el nombre de la sala formada por las dos cartas mostradas, Alcantarillas e Inundado, sería las Alcantarillas inundadas).

- Indicaciones para poblar los 12 espacios numerados de la carta de sala (i). Cada monstruo tiene indicaciones para partidas de 2, 3 y 4 jugadores, igual que en la preparación normal de un escenario.

- Descripciones del contenido de cualquier pieza de Tesoro (j). Aunque las piezas de Tesoro de las mazmorras aleatorias nunca contendrán elementos importantes para la campaña, pueden contener diversos beneficios útiles para los jugadores.

- Indicaciones de los tipos de trampa (k). Ten en cuenta que el símbolo de daño rojo (l) indica que la trampa es una de daño.

## Créditos

---

## Guía rápida de iconos

> Reconstruida de la lámina de la página 52. Los iconos son dibujos y no se conservan al extraer el texto; queda el nombre de cada uno y la página donde se explica.

### Iconos generales

| Icono | Pág. |
|---|---|
| Iniciativa | 18 |
| Movimiento | 19 |
| Salto | 19 |
| Vuelo | 19 |
| Ataque | 19 |
| Alcance | 19 |
| Hexágono de ataque | 21 |
| Hexágono de jugador | 21 |
| Objetivo | 21 |
| Bonificación continua | 25 |
| Bonificación de ronda | 25 |
| Escudo | 25 |
| Represalia | 26 |
| Curación | 26 |
| Saqueo | 27 |
| XP | 27 |
| Espacio de uso | 25 |
| Espacio de uso: Obtén XP | 27 |
| Perdida o consumida | 8, 17 |
| Gastar objeto | 8 |
| No se puede recuperar | 27 |
| Capacidad de recuperación | 27 |
| Reponer objeto | 27 |
| Modificador de ataque –1 | 8 |
| Nivel | 12 |
| Barajar mazo | 32 |
| Retirar de la partida | 39 |
| Devolver al mazo | 39 |

### Nivel del escenario y dificultad

Nivel sugerido: nivel medio del grupo ÷ 2, redondeando hacia arriba (consulta «Nivel del escenario», pág. 15).

| Dificultad | Modificación de nivel |
|---|---|
| Fácil | –1 |
| Normal | +0 |
| Difícil | +1 |
| Muy difícil | +2 |

| Nivel del escenario | Nivel de los monstruos | Conversión de oro | Daño de las trampas | Experiencia extra |
|---|---|---|---|---|
| 0 | 0 | 2 | 2 | 4 |
| 1 | 1 | 2 | 3 | 6 |
| 2 | 2 | 3 | 4 | 8 |
| 3 | 3 | 3 | 5 | 10 |
| 4 | 4 | 4 | 6 | 12 |
| 5 | 5 | 4 | 7 | 14 |
| 6 | 6 | 5 | 8 | 16 |
| 7 | 7 | 6 | 9 | 18 |

### Iconos de elementos

Consulta «Inducciones elementales» (pág. 24).

Fuego · Hielo · Aire · Tierra · Luz · Oscuridad · Cualquier elemento · Usar elemento

### Estados y efectos

Consulta «Estados» (págs. 22-23).

BENDICIÓN · MALDICIÓN · DESARME · INMOVILIZACIÓN · HERIDA · CONFUSIÓN · FORTALECIMIENTO · EMPUJÓN · TIRÓN · PERFORANTE · AÑADIR OBJETIVO · INVISIBILIDAD · ATURDIMIENTO · VENENO

### Espacios de equipo

Consulta «Cartas de Objeto» (pág. 8).

Cabeza · Cuerpo · Piernas · Una mano · Dos manos · Objeto pequeño

### Mejorar

Consulta «Mejorar cartas de Capacidad» (págs. 45-47).

### Cartas

| Mazo | Pág. |
|---|---|
| Misión personal | 38 |
| Diseño de objeto | 38 |
| Escenario secundario aleatorio | 38 |
| Evento de camino | 39 |
| Evento de ciudad | 39 |
| Capacidad de personaje | 7 |
| Objeto | 8 |
| Capacidad de monstruo | 10 |
| Objetivo de batalla | 10 |
| Modificador de ataque | 11 |
| Mazo de Salas | 50 |
| Mazo de Monstruos | 51 |

### Clave de monstruos

Consulta «Página de escenario» (pág. 13). Cada hexágono se divide en tres secciones: arriba a la izquierda para dos personajes, arriba a la derecha para tres y abajo para cuatro.

Monstruo no presente (negro) · Monstruo normal (blanco) · Monstruo de élite (amarillo)

---

## Contenido de la caja

- 47 cartas de Atributos de monstruo
- 1 reglamento
- 18 figuras de personaje
- 24 cartas de Objetivo de batalla
- 50 fichas de Dinero
- 24 cartas de Misión personal
- 46 fichas de Daño
- 17 tarjetas de personaje
- 6 fundas de atributos de monstruo
- 1 Libro de escenarios
- 10 fichas de Referencia de escenario
- 9 cartas de Escenario aleatorio
- 504 cartas de Capacidad de personaje
- 150 cartas de Evento
- 4 diales de PS/XP
- 1 Libro de anales de la ciudad
- 40 cartas de Mazmorra aleatoria
- 457 cartas de Modificador de ataque
- 12 fichas de Objetivo
- 253 cartas de Objeto
- 1 mapa
- 4 cartas de Referencia de jugador
- 17 blocs de personaje
- 236 figuras troqueladas de monstruo
- 6 discos de elemento de madera
- 32 fichas de Invocación
- 1 bloc de grupo
- 232 cartas de Capacidad de monstruo
- 30 piezas de Tablero de doble cara
- 1 tabla de inducción elemental
- 3 sobres cerrados
- 60 fichas de Estado
- 35 cajas de personaje
- 155 piezas de Terreno de doble cara
- 4 hojas de pegatinas
- 85 fichas de Personaje
- 24 soportes de plástico
- 1 marcador de ronda