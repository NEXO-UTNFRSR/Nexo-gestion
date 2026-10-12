name: Incidente Crítico (Expedite)
about: Reporte y seguimiento de incidentes P1 en producción
title: '[P1][Expedite] '
labels: 'cos:expedite, tipo:bug-critico, tipo:incidente'
assignees: ''
---

# Detalle del Incidente
- **Severidad:** P1 - Crítica
- **Impacto:** [Descripción del impacto en producción o usuarios de campo]
- **Hora Detección:** HH:MM HS
- **Incident Commander:** [Ops Lead / SRE]

---

### Timeline de Respuesta
- `HH:MM` - **Detección:** Alerta de monitoreo / Reporte del cliente. Se crea tarjeta Expedite y se salta el límite de WIP.
- `HH:MM` - **Swarming:** Equipo reunido (SRE + Tech Lead + Devs).
- `HH:MM` - **Mitigación:** [Acción de mitigación aplicada].
- `HH:MM` - **Restablecimiento:** Servicio recuperado. **MTTR:** XX minutos.

---

### Post-Mortem y Acciones Preventivas
- [ ] Archivo de post-mortem creado en `docs/postmortem-XXX.md` (dentro de las 48 h).
- [ ] Acción preventiva ingresada como ítem `cos:intangible` o `cos:standard` en el backlog.