# Laboratorio 04 - Modelación y Simulación (2026)

### 1. Problema 2: Modelo de Producción y Períodos Múltiples (ACME Manufacturing)

* **Objetivo:** Minimizar costo total de producción e inventario durante 6 meses con capacidad máxima de 225 ventanas/mes.
* **Costo Óptimo Total:** **$61,795.00**
* **Producción e Inventarios:**

  * Mes 1: Prod = 205 | Inv Final = 25

  - Mes 2: Prod = 225 (Capacidad máx) | Inv Final = 0
  - Mes 3: Prod = 190 | Inv Final = 0
  - Mes 4: Prod = 160 | Inv Final = 20
  - Mes 5: Prod = 225 (Capacidad máx) | Inv Final = 25
  - Mes 6: Prod = 225 (Capacidad máx) | Inv Final = 0
* **Inciso c:** La solución continua y entera son idénticas ($61,795.00) por la naturaleza discreta del balance de inventario.

---

### 2. Problema 3: Modelo de Asignación de Horarios de Buses (Ciudad de Guatemala)

* **Objetivo:** Minimizar la flota diaria de autobuses para cubrir la demanda variable en 6 tramos horarios de 4 horas continuas.
* **Total Mínimo de Autobuses:** **26 autobuses**
* **Distribución de Turnos:**
  * Turno 2 (04:00 AM - 12:00 PM): **10 buses**
  * Turno 4 (12:00 PM - 08:00 PM): **12 buses**
  * Turno 6 (08:00 PM - 04:00 AM): **4 buses**

---

### 3. Problema 4: Modelo de Renovación Urbana (Ciudad de Mixco)

* **Objetivo:** Maximizar impuestos anuales tras la demolición de 300 viviendas (terreno disponible = 63.75 acres) con presupuesto máximo de $15,000,000.
* **Solución Continua:** **$355,555.55** (185.19 viviendas).
* **Solución Entera:** **$355,400.00** (180 viviendas: 36 sencillas, 99 dobles, 31 triples, 14 cuádruples).
* **Análisis:** Exigir solución discreta solo reduce la recaudación en $155.55 (0.04%), ofreciendo una asignación ejecutable que consume el 100% del presupuesto ($15M) y 53.60 acres de terreno.

---

## Cómo Ejecutar

```bash
# Activar entorno virtual
source .venv/bin/activate

# Abrir el cuaderno de Jupyter
jupyter notebook Laboratorio04.ipynb
```
