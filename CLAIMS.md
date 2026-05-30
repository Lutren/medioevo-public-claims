# MEDIOEVO — Registro Público de Claims de Autoría

**Autor:** Luis René González López (GitHub: @Lutren)
**Email de contacto:** jaciel.medrano@gmail.com
**Fecha de publicación:** 2026-05-30
**Repositorio:** github.com/Lutren/medioevo-public-claims

Este documento registra claims de autoría e ideas originales del ecosistema MEDIOEVO.
No reemplaza documentación legal pero establece prior art público con timestamps verificables.

---

## CLAIM-001: Observacionismo (framework epistémico)

**Descripción:** Framework epistémico de tres operadores aplicado tanto a literatura como a diseño de sistemas de IA:
- Observar sin prejuicio
- Documentar sin juicio
- Actuar sin distracción

**Origen:** Desarrollado por L.R. González circa 2014-2016 de manera independiente, antes de trabajar con IA, a partir de observar múltiples descripciones válidas del mismo evento (la noche leyendo a Nietzsche). El término existía previamente pero fue objeto de reivindicación matemática con formalización de axiomas y operadores.

**Primera aplicación pública documentada en git:** Branch `main` de este repositorio.
**Evidencia adicional:** Corpus de 22 años en sistema de archivos local con hashes SHA-256.

---

## CLAIM-002: OSIT — Framework de firmware cognitivo para IA

**Descripción:** Propuesta de arquitectura para una capa de "firmware cognitivo" en sistemas de IA que gestiona:
- La diferencia entre certeza e inferencia
- El residuo epistémico (R) como métrica de incertidumbre
- La función `estimate_epistemic_state(R)` como operador canónico

**Origen:** Desarrollado por L.R. González durante 2023-2026, formalizado en BRAIN_OS (21 documentos maestros).

**Versión documentada:** MEDIOEVO_OSIT_MASTER_CANON_v12_0_1 (hash en sistema de archivos local).

---

## CLAIM-003: TUIP-Σ — Teoría Unificada de Información-Percepción

**Descripción:** Framework físico-informacional que trata la percepción como un proceso de un sistema de información procesando a otro sistema de información. Formaliza con operadores matemáticos la relación entre observador, estado del sistema y colapso de estado.

**Origen:** Desarrollado por L.R. González. Documentado en:
- `Deconstrucción Observacionista de la Física — TUIP-Σ OSIT.pdf`
- `Deconstrucción Observacionista de la Inteligencia — TUIP-Σ OSIT.pdf`
- `06_HIPOTESIS_FISICAS_OSIT_TUIP_SIGMA.md`

---

## CLAIM-004: Observacionismo Inverso

**Descripción:** Técnica de auditoría que va desde los outputs observados hacia los axiomas implícitos que los generaron. Pregunta: dado que el sistema produce X, ¿qué axiomas implícitos lo generaron necesariamente?

**Aplicaciones:** Depuración de código, auditoría de modelos de IA, análisis literario, análisis epistemológico.

**Documentado en:** `AUDITORIA_OBSERVACIONISTA_INVERSA_MEDIOEVO_v3_COMPLEMENTADA.pdf`

---

## CLAIM-005: Motor de Colapso por Observador (DUAT)

**Descripción:** Aplicación del principio de colapso cuántico al diseño de simuladores multi-agente: el estado del sistema colapsa diferente según quién lo observa, implementado como mecanismo de juego/simulación.

**Contexto:** Parte del motor DUAT Agent City Engine (GlomoRender).

**Evidencia técnica:** 314 tests pasando en 106 archivos de test. Typecheck PASS. Build PASS (Vite 5.4.21, 249 módulos).

---

## CLAIM-006: MEDIOEVO — Saga literaria sci-fi

**Descripción:** Saga de ciencia ficción de 35 libros (~3,000,000 palabras) iniciada en 2001. Estructuralmente no-lineal (influencia Chrono Trigger / Rayuela). Temas centrales: física de la información, conciencia como hardware, observación participativa.

**Inicio documentable:** ~2001. Autor tenía 14 años. Primeros libros: los 13 originales tras 26 años de estructura.

**Protección:** Copyright de obra literaria. No requiere registro adicional para protección en México (convenio de Berna).

---

## CLAIM-007: FCU v2.0 — Framework de Continuidad Universal

**Descripción:** Protocolo de handoff entre sesiones de IA que permite a cualquier agente nuevo orientarse en un ecosistema complejo leyendo cinco documentos en orden definido. Solución al problema de pérdida de contexto entre sesiones de LLM.

**Componentes:** CLAUDE.md, PENDIENTES_MASTER.md, NEXT_SESSION_BRIEF.md, HANDOFF_MAESTRO_UNIFICADO.md, INVENTARIO_MAESTRO.md.

---

## CLAIM-008: Curador SETO — Arquitectura de curaduría de conocimiento

**Descripción:** Sistema de curaduría que asigna a cada fuente: hash SHA-256, ficha Markdown, estado (ARCHIVO_FRIO / BLOQUEADO / BASURA_REGENERABLE / BORRADO_DUPLICADO), y lane temático. SQLite como base consultable, Markdown como capa humana.

**Estado actual:** 337 fuentes procesadas.

---

## CLAIM-009: Métricas LG (Landauer-Gini) para simulación de ciudades

**Descripción:** Combinación de la eficiencia informacional de Landauer con el índice de Gini de distribución de recursos, aplicada a simular distribución de riqueza/poder en ciudades de agentes.

**Implementación:** `src/duatGenesis/metrics.ts` — MetricsTracker, LG spectrum, dim_obs, atumScore, osirisScore, liveness, residue, Phi_eff, clipArtifactRatio, cosmology classification.

---

## CLAIM-010: Wabi-Sabi Codegen — Gate de codegen LLM-local con plan_runner autónomo

**Descripción:** Sistema de generación de código por LLM local con:
- Gate de activación explícito (WABI_LLM_CODEGEN=1)
- plan_runner autónomo y resumible (puede interrumpirse y continuar donde quedó)
- Separación estricta entre modo análisis y modo construcción

**Filosofía:** Las herramientas que modifican su propio sistema de ejecución requieren gate explícito (principio de disciplina epistémica).

---

## CLAIM-011: Conway — Sistema de agentes paralelos persistentes

**Descripción:** Arquitectura de 8 agentes corriendo en paralelo 24/7, coordinados por un Hub central, con memoria persistente compartida (MemPalace), para producir trabajo que ningún agente individual puede hacer solo.

**Nombre:** Homenaje a John Horton Conway (reglas simples → complejidad emergente).

---

## Notas sobre este registro

1. Este documento **no es una patente** y no tiene el mismo peso legal. Es un registro de prior art público.
2. Los hashes SHA-256 de los archivos fuente están en `runtime/curador_seto/curador_index.sqlite` (no publicado por contener rutas privadas, disponible para verificación bajo solicitud).
3. Los commits de git tienen timestamps Unix verificables.
4. La licencia de este repositorio es CC BY 4.0: la información es libre con atribución.
5. Para reclamos formales de IP sobre la obra literaria MEDIOEVO, aplica el Convenio de Berna automáticamente desde la creación.

---

*L.R. González — 2026-05-30 — github.com/Lutren*
