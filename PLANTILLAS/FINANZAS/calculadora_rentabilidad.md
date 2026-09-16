# Calculadora de Rentabilidad — Inversionista

## Propósito
Calcular la rentabilidad de una propiedad para asesorar a un inversionista.

**Este documento es la herramienta clave para asesorar a inversionistas.**

---

## 1. Datos de Entrada

| Dato | Valor |
| :--- | :--- |
| Precio de compra | $ |
| Precio de venta (o valor actual) | $ |
| Pie (20-30%) | $ |
| Gastos operacionales (notaría, escritura) | $ |
| Arriendo mensual | $ |
| Contribuciones trimestrales | $ |
| Gastos comunes mensuales | $ |
| Dividendo mensual (si aplica) | $ |
| Meses desocupados al año | |

---

## 2. Fórmulas

### 2.1 ROE (Retorno sobre Patrimonio)

**Fórmula:**
ROE = (Precio de venta - Precio de compra) / (Pie + Gastos operacionales)


**Ejemplo:**
- Precio de compra: $40.000.000
- Precio de venta: $51.000.000
- Pie: $8.000.000
- Gastos operacionales: $500.000

ROE = ($51.000.000 - $40.000.000) / ($8.000.000 + $500.000)
ROE = $11.000.000 / $8.500.000
ROE = 1,29 = 129%


**Interpretación:** El inversionista multiplicó su inversión por 2,29 en 2 años.

### 2.2 ROA (Retorno sobre Activos)

**Fórmula:**
ROA = (Ingresos anuales - Gastos anuales) / Valor de la propiedad


**Dónde:**
- Ingresos = Arriendo mensual × 12
- Gastos = Contribuciones × 4 + Gastos comunes × 12

**Ejemplo:**
- Arriendo: $390.000 × 12 = $4.680.000
- Contribuciones: $20.000 × 4 = $80.000
- Gastos comunes: $0
- Valor propiedad: $85.000.000

ROA = ($4.680.000 - $80.000) / $85.000.000
ROA = $4.600.000 / $85.000.000
ROA = 0,0541 = 5,41%


**Interpretación:** La propiedad genera un 5,41% anual sobre su valor total.

### 2.3 ROI Apalancado

**Fórmula:**
ROI = (Ingresos - Gastos - Dividendo) / (Pie + Gastos operacionales)

**Ejemplo:**
- Arriendo: $390.000 × 12 = $4.680.000
- Contribuciones: $80.000
- Dividendo: $250.000 × 12 = $3.000.000
- Pie: $17.000.000
- Gastos operacionales: $700.000

ROI = ($4.680.000 - $80.000 - $3.000.000) / ($17.000.000 + $700.000)
ROI = $1.600.000 / $17.700.000
ROI = 0,0904 = 9,04%


**Interpretación:** Con apalancamiento, la rentabilidad sube de 5,41% a 9,04%.

### 2.4 Tasa de Vacancia

**Fórmula:**
Tasa de vacancia = Meses desocupados / 12


**Ejemplo:**
- Meses desocupados: 1
- Tasa de vacancia = 1 / 12 = 8,33%

**Interpretación:** La propiedad está desocupada el 8,33% del año.

### 2.5 Cap Rate

**Fórmula:**
Cap Rate = Arriendo anual / Valor de la propiedad


**Ejemplo:**
- Arriendo anual: $4.680.000
- Valor propiedad: $85.000.000
- Cap Rate = $4.680.000 / $85.000.000 = 5,5%

**Interpretación:** La propiedad genera un 5,5% anual sobre su valor.

---

## 3. Fórmula Inversa — Precio Máximo Inversionista

**Fórmula:**
Precio máximo = Arriendo anual / Rentabilidad esperada


**Ejemplo:**
- Arriendo anual: $4.680.000
- Rentabilidad esperada: 6%
- Precio máximo = $4.680.000 / 0,06 = $78.000.000

**Interpretación:** Un inversionista que busca 6% de rentabilidad pagaría máximo $78.000.000.

---

## 4. Fórmula Inversa — Rentabilidad Implícita

**Fórmula:**
Rentabilidad implícita = Arriendo anual / Precio de venta


**Ejemplo:**
- Arriendo anual: $4.680.000
- Precio de venta: $85.000.000
- Rentabilidad implícita = $4.680.000 / $85.000.000 = 5,5%

**Interpretación:** Al precio de venta, la propiedad ofrece un 5,5% de rentabilidad.

---

## 5. Hoja de Cálculo (Llena)

| Indicador | Fórmula | Resultado |
| :--- | :--- | :--- |
| **ROE** | (Venta - Compra) / (Pie + Gastos) | |
| **ROA** | (Ingresos - Gastos) / Valor | |
| **ROI** | (Ingresos - Gastos - Dividendo) / (Pie + Gastos) | |
| **Vacancia** | Meses desocupados / 12 | |
| **Cap Rate** | Arriendo anual / Valor | |
| **Precio máx. inversionista** | Arriendo anual / Rentabilidad | |
| **Rentabilidad implícita** | Arriendo anual / Precio | |

---

## 6. Documentos Relacionados

- `04_DEPT_FINANZAS.md` — Departamento Finanzas
- `06_DEPT_INVERSIONES.md` — Departamento Inversiones
- `PLANTILLAS/VENTA/informe_valoracion.md` — Informe de Valoración
