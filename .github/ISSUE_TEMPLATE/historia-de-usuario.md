---
name: Historia de Usuario
about: Plantilla estándar para Historias de Usuario de Nexo
title: 'HU-XX: '
labels: 'tipo:historia, cos:standard'
assignees: ''
---

## Historia
Como [persona], quiero [capacidad], para [beneficio].

**Detalles de Gestión:**
- **Épica:** E1 / E2 / E3
- **Squad:** Core IA / Dispositivo AR / Plataforma de Comando
- **Prioridad:** Crítica / Alta / Media
- **Sprint:** Sprint 1 / Sprint 2 / Sprint 3
- **Estimación:** SP
- **Depende de:** — (o HU-0X)
- **OKR / KR:** OKR 1 - KRX / OKR 2 - KRX

## Criterios INVEST
- **I**ndependiente: 
- **N**egociable: 
- **V**aliosa: 
- **E**stimable: 
- **S**mall (≤ 8 SP): 
- **T**esteable: 

## Criterios de Aceptación (BDD / Gherkin)

```gherkin
Escenario 1: [Nombre del escenario principal]
  Dado que [condición inicial]
  Cuando [acción ejecutada]
  Entonces [resultado esperado]

Escenario 2: [Nombre del escenario de borde o error]
  Dado que [condición inicial]
  Cuando [acción ejecutada]
  Entonces [resultado esperado]