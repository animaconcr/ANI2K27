# DECISIONS.md — Decisiones cerradas · AnimaCon
 
*Last updated: 2026-06-01 · Owner: V*
 
> Por qué se decidió algo, para **NO reabrirlo**. Solo se revierte una decisión si
> aparece **data nueva** que la invalide (y entonces se registra el cambio acá, no se borra).
 
---
 
| Fecha | Decisión | Razón |
|---|---|---|
| 2026-06-01 | El proyecto adapta el repo *marketing-skills* (Corey Haines) a AnimaCon vía **fork**, no se reescribe de cero | Las skills son casi product-agnósticas; leen los docs de contexto. Reescribir todo = overengineering |
| 2026-06-01 | **Podadas 8 skills puro-SaaS**: `aso`, `paywalls`, `churn-prevention`, `onboarding`, `signup`, `popups`, `programmatic-seo`, `directory-submissions` | No aplican a un evento B2C recurrente |
| 2026-06-01 | **Reencuadradas 9 skills B2B/evento** hacia patrocinios/stands/entradas (bloque "Contexto AnimaCon" + disparadores) | El motion SaaS→evento mapea 1:1 (prospecto=marca, deal=patrocinio/stand) |
| 2026-06-01 | **Workflow = app de Claude (Proyecto)**, NO Claude Code/terminal | El owner no trabaja en terminal; las skills no necesitan autodisparo para el uso real |
| 2026-06-01 | **Knowledge mínimo del proyecto** = `MOTHER.md` + `product-marketing.md` + `sponsorship-sales.md` + `DATOS.md` + `DECISIONS.md` + `QA.md`. Las 35 skills son molde opcional | Los docs de contexto son el motor; las skills agregan estructura, no datos |
| 2026-06-01 | **Prioridad de temporada (orden fijo)**: 1) patrocinios, 2) entradas, 3) stands, 4) comunidad | Definido por el owner |
| 2026-06-01 | Mapeo SaaS→evento documentado en `sponsorship-sales.md` (prospecto=marca, deck=media kit, pipeline=embudo de marcas) | Evita que las skills inventen un ICP de SaaS |
 
## Aprendizajes / correcciones registradas
- 2026-06-01 — La recomendación inicial de usar Claude Code asumía perfil técnico/terminal. Corregido: el owner opera en la app. Las skills pasan de "esencial" a "molde opcional".
 
