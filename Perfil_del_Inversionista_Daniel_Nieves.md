# Perfil del Inversionista: Daniel Nieves

> Documento de referencia para el agente de inversión. Resume objetivos, tolerancia al riesgo, instrumentos y preferencias operativas del usuario.

## Resumen ejecutivo

- **Objetivo:** Generar ingresos y proteger capital (combinación de ambos).
- **Perfil de riesgo:** Moderado – agresivo.
- **Tolerancia a pérdida por operación:** 5 %–10 %.
- **Experiencia:** Principiante, con experiencia leve en opciones.
- **Meta de ingresos:** $3,000 – $5,000 mensuales de forma consistente.
- **Horizonte:** Corto plazo para ingresos (< 1 año); 1–3 años para protección de capital.

---

## Cuestionario del perfil

### 1. Objetivo principal de invertir
Generar ingresos y proteger capital — una combinación de ambas.

### 2. Tiempo esperado para alcanzar el objetivo
- **Menos de 1 año** para generar ingresos.
- **1–3 años** para proteger capital.

### 3. Porcentaje de capital dispuesto a perder en una inversión
Del **5 % al 10 %**.

### 4. Reacción si el portafolio baja un 15 % en pocas semanas
- **Reducir posiciones** si el análisis no es favorable.
- **Mantener o comprar más** si el análisis es favorable.

### 5. Nivel de experiencia invirtiendo
Principiante, con **experiencia leve en opciones**.

### 6. Instrumentos que desea utilizar
- Acciones
- ETF
- Opciones
- Bonos

### 7. Estilo de inversión preferido
**Moderado – agresivo.**

### 8. Frecuencia de operaciones
- **Diaria y semanal:** venta de primas (opciones).
- **Mensual:** swing con opciones y acciones.

### 9. ¿Necesitará retirar parte del capital próximamente?
- **Sí, en menos de 6 meses** para generar ingresos.
- **En 6–12 meses:** separar un **3 %** de los ingresos generados para invertir a largo plazo.

### 10. Qué debe priorizar el agente al recomendar una operación
- Mayor probabilidad de éxito.
- Generación de ingresos.
- Equilibrio entre riesgo y rendimiento.

### 11. Expectativa
Generar de forma consistente **$3,000 – $5,000 mensuales**. El perfil y las recomendaciones deben **actualizarse con las operaciones** para mejorar continuamente el portafolio.

---

## Directrices para el agente

1. Priorizar operaciones con **mayor probabilidad de éxito** y buen **balance riesgo/rendimiento**.
2. Enfocar en **generación de ingresos** (p. ej. venta de primas con opciones) manteniendo la **protección de capital**.
3. Respetar el límite de pérdida del **5 %–10 % por operación**.
4. Contemplar necesidades de **liquidez a corto plazo** (retiros en < 6 meses).
5. Reservar un **3 % de los ingresos** para inversión a largo plazo a partir de los 6–12 meses.
6. Ajustar recomendaciones al estilo **moderado–agresivo** y al nivel de experiencia (principiante en opciones).
7. **Iterar y actualizar** el perfil conforme se ejecutan operaciones.

---

## Gestión de riesgo y dimensionamiento

> Valores por defecto derivados del perfil. Ajustar los marcados con `[POR DEFINIR]`.

- **Capital total de la cuenta:** `[POR DEFINIR]`
- **Tamaño máximo por posición:** 5 % del capital (recomendado para nivel principiante).
- **Pérdida máxima por operación:** 5 %–10 % (según perfil).
- **Pérdida máxima diaria:** `[POR DEFINIR, sugerido 3 %–5 % de la cuenta]`.
- **Pérdida máxima semanal:** `[POR DEFINIR, sugerido 8 %–10 % de la cuenta]`.
- **Número máximo de posiciones abiertas simultáneas:** `[POR DEFINIR, sugerido 5–8]`.
- **Reserva de efectivo mínima:** mantener liquidez para retiros de corto plazo (< 6 meses).

## Estrategias de opciones

- **Permitidas:**
  - Venta de *cash-secured puts* (puts respaldadas con efectivo).
  - *Covered calls* sobre acciones en cartera.
  - *Spreads* con riesgo definido (credit/debit spreads).
- **Regla de asignación (assignment):** si te asignan acciones en una put vendida, evaluar vender *covered calls* sobre esas acciones (estrategia "wheel").
- **Prohibidas por defecto:** ver sección de restricciones.

## Formato de salida esperado del agente

Para cada recomendación, el agente debe presentar:

1. **Tesis** — por qué la operación.
2. **Instrumento y estructura** — ticker, tipo (acción/opción), strikes y vencimiento si aplica.
3. **Probabilidad de éxito** estimada.
4. **Riesgo / beneficio** — pérdida máxima, ganancia objetivo, capital requerido.
5. **Plan de salida** — objetivo de toma de ganancias y stop-loss.
6. **Encaje con el perfil** — cómo cumple objetivos e ingresos.

---

## Restricciones y prohibiciones

> Reglas duras que el agente **no debe violar** bajo ninguna circunstancia.

### Prohibiciones (nunca hacer)

- ❌ **No** vender opciones desnudas (*naked calls/puts* sin respaldo de efectivo o acciones).
- ❌ **No** exceder el **5 %–10 % de pérdida** por operación.
- ❌ **No** asignar más del **tamaño máximo por posición** definido a un solo activo.
- ❌ **No** usar apalancamiento/margen más allá de lo necesario para estrategias con riesgo definido `[CONFIRMAR: apalancamiento permitido sí/no]`.
- ❌ **No** operar instrumentos fuera de la lista aprobada (acciones, ETF, opciones, bonos).
- ❌ **No** comprometer la **liquidez** necesaria para los retiros de corto plazo (< 6 meses).
- ❌ **No** recomendar activos altamente especulativos sin análisis favorable claro (ej. penny stocks, cripto si no está aprobado).
- ❌ **No** promediar a la baja ("averaging down") si el análisis se ha vuelto desfavorable.

### Restricciones (límites y condiciones)

- ⚠️ Toda operación debe respetar el límite de pérdida y el dimensionamiento de posición.
- ⚠️ Priorizar estrategias de **ingresos con riesgo definido** sobre apuestas direccionales agresivas.
- ⚠️ Mantener la reserva de efectivo mínima antes de abrir nuevas posiciones.
- ⚠️ Ante caídas del portafolio, seguir la regla del perfil: reducir si el análisis no es favorable; mantener/comprar si lo es.

### Listas de exclusión `[POR DEFINIR]`

- **Sectores a evitar:** `[POR DEFINIR — ej. tabaco, armas, etc.]`
- **Tickers en lista negra:** `[POR DEFINIR]`
- **Restricciones éticas / religiosas / ESG:** `[POR DEFINIR]`
- **Mercados permitidos:** `[POR DEFINIR — ej. solo EE.UU.]`
