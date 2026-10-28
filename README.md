# SaforPista

Aplicació web per a la gestió de clubs de tennis i pàdel de la Safor: reserves de pistes, escola esportiva, nivells de joc, pagaments i avisos, tot en un sol lloc.

Projecte P5 (Idea de negoci) del mòdul 0492 Projecte Intermodular, 2n DAW, curs 2026-27.
Autora: Maria Escrivà.

## El problema

Molts poliesportius i clubs de la comarca encara gestionen les reserves amb llibretes, telèfon i grups de WhatsApp. Això provoca dobles reserves, places de classe que es perden, avisos que no arriben i pagaments difícils de controlar.

## La solució

Una aplicació web amb dos perfils:

- **Jugador:** reservar i cancel·lar pistes, apuntar-se a partides obertes, confirmar o anul·lar l'assistència a classe, demanar canvi de grup, consultar el nivell i pagar.
- **Administració i monitors:** gestionar pistes i horaris, organitzar l'escola per grups i nivells, controlar l'assistència, registrar cobraments i enviar comunicacions oficials.

Es comercialitzarà com a servei de subscripció (SaaS) per a polisportius municipals, clubs i empreses esportives.

## Stack tecnològic

| Part | Tecnologia |
| --- | --- |
| Frontend | React |
| Backend | Node.js + Express (API REST) |
| Base de dades | MySQL |
| Control de versions | Git i GitHub |

## Estructura del repositori

```
saforpista/
├── frontend/   Aplicació client en React
├── backend/    API REST en Node.js amb Express
├── database/   Scripts SQL (creació de taules i dades de prova)
└── docs/       Documentació del projecte i wireframes
```

## Branques

- `main`: versió estable.
- `develop`: desenvolupament; els canvis passen a `main` quan funcionen.

## Objectius de Desenvolupament Sostenible

- ODS 3, Salut i benestar: facilita la pràctica esportiva.
- ODS 9, Indústria, innovació i infraestructura: digitalitza xicotetes entitats esportives.

## Estat

Fase 1: inicialització i anàlisi de necessitats (RA1).
