# Clases de Servicio - Nexo

El trabajo en Nexo se clasifica en cuatro clases de servicio según su costo del retraso y urgencia:

1. 🔴 **Expedite (P1 Crítico):**
   - Aplicable a caídas del sistema, brechas de seguridad o latencia que excede el SLO de 300 ms.
   - **Exento de los límites de WIP.** Máximo 1 ítem Expedite activo simultáneo por equipo.
   - Atención inmediata en enjambre (*swarming*).
   - Meta de mitigación: ≤ 30 minutos. Meta de resolución: ≤ 4 horas.
   - Exige post-mortem sin culpa en ≤ 48 horas.

2. 🟡 **Fixed Date:**
   - Entregas con plazo contractual o regulatorio (ej. Auditoría externa de sesgo en mes 9, Certificación AI Act en mes 12).
   - Se prioriza sobre Standard a medida que se acerca la fecha límite.

3. 🟢 **Standard:**
   - Historias de usuario del flujo normal del Sprint.
   - Sigue los límites de WIP estipulados y la Ley de Little.

4. ⚪ **Intangible:**
   - Deuda técnica, refactorizaciones y actualizaciones de dependencias.
   - Se reserva un mínimo del 15 % de la capacidad de cada Sprint.