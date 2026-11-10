# Especificació funcional de SaforPista

Històries d'usuari de l'aplicació (entrega 1.B de P5). Format: *com a [rol], vull [acció] per a [benefici]*.

- **MVP**: entren en la primera versió.
- **Mitjana**: s'afegiran quan el MVP funcione.

## Jugador o jugadora

| ID | Història | Criteri d'acceptació | Prioritat |
| --- | --- | --- | --- |
| HU01 | Com a jugadora, vull registrar-me i iniciar sessió per a accedir a les meues reserves i classes | Amb correu i contrasenya correctes entre; amb dades incorrectes, missatge d'error | MVP |
| HU02 | Com a jugadora, vull veure quines pistes estan lliures per dia i hora per a triar quan jugar | El calendari mostra en colors diferents les franges lliures i ocupades | MVP |
| HU03 | Com a jugadora, vull reservar una pista (tennis o pàdel, interior o exterior) per a no haver de telefonar | La reserva apareix al calendari i ningú més pot reservar la mateixa pista a la mateixa hora | MVP |
| HU04 | Com a jugadora, vull cancel·lar una reserva per a deixar la pista lliure a altres | En cancel·lar, la franja torna a estar lliure al moment | MVP |
| HU05 | Com a alumna de l'escola, vull confirmar que vaig a classe o avisar que no vinc per a no haver d'escriure al monitor | El monitor veu l'estat de cada alumne i la plaça queda lliure si avise de baixa | MVP |
| HU06 | Com a jugadora, vull rebre els avisos del club dins de l'aplicació per a assabentar-me de cancel·lacions sense WhatsApp | Els avisos nous apareixen en destacat en entrar | MVP |
| HU07 | Com a alumna que treballa a torns, vull demanar canvi a un altre grup del meu nivell per a no perdre classes | La sol·licitud arriba a l'administració, que l'accepta o la rebutja | Mitjana |
| HU08 | Com a jugadora, vull veure el meu nivell de joc per a apuntar-me a partides equilibrades | El perfil mostra el nivell assignat pel monitor | Mitjana |
| HU09 | Com a jugadora, vull apuntar-me a partides obertes on falta gent per a jugar encara que no tinga parella | Es veuen les partides amb places lliures i el nivell demanat | Mitjana |
| HU10 | Com a jugadora, vull veure els meus pagaments per a saber si tinc algun mes pendent | Llistat de quotes pagades i pendents | Mitjana |

## Administració i monitors

| ID | Història | Criteri d'acceptació | Prioritat |
| --- | --- | --- | --- |
| HU11 | Com a recepcionista, vull bloquejar una pista per pluja o manteniment perquè ningú la reserve | La pista bloquejada no es pot reservar i els afectats reben un avís | MVP |
| HU12 | Com a responsable de l'escola, vull crear grups amb nivell, horari, places i monitor per a organitzar les classes | El grup apareix a l'escola i no s'hi poden apuntar més alumnes que places | MVP |
| HU13 | Com a monitor, vull veure l'assistència de cada grup per a saber qui vindrà | Llista d'alumnes amb el seu estat: confirma, baixa o sense resposta | MVP |
| HU14 | Com a recepcionista, vull enviar un avís a tots els socis o a un grup per a deixar de fer-ho per WhatsApp | L'avís arriba a les persones triades i queda guardat | MVP |
| HU15 | Com a monitor, vull assignar o canviar el nivell d'un jugador per a fer grups equilibrats | El nou nivell es veu al perfil del jugador | Mitjana |
| HU16 | Com a recepcionista, vull registrar els pagaments per a saber qui ha pagat i qui deu | Llistat de socis amb l'estat de cada quota | Mitjana |
| HU17 | Com a responsable de l'escola, vull acceptar o rebutjar canvis de grup per a controlar les places | En acceptar, l'alumne passa al grup nou i la plaça vella queda lliure | Mitjana |

## Fora de la primera versió

Llista d'espera automàtica, pagament en línia real, rànquing per resultats, tornejos, multisede, xat i informes avançats.

## Stack tecnològic

| Capa | Tecnologia |
| --- | --- |
| Frontend | React |
| Backend | Node.js + Express (API REST) |
| Base de dades | MySQL |
| Seguretat | JWT (sessió i rols) + bcrypt (contrasenyes) |
| Control de versions | Git, GitHub i GitHub Projects |
| Desplegament | Nginx davant de Node.js (allotjament per decidir a la fase 2) |

La justificació de cada tecnologia és a l'entrega 1.B (`Entrega_1B_SaforPista.docx`).
