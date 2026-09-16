[ 🌐 عربي ](README.ar.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Kit Excel de Referencia de Cálculo de Costo Landed y Reconciliación de Cadena de Suministro

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-217346.svg)
![Tool Type](https://img.shields.io/badge/Type-Decision%20Support-2251FF.svg)

**<p>Calculadora de Costo Landed y Plantilla de Reconciliación: Una herramienta de referencia profesional para validar cálculos de costo landed de cadena de suministro, reconciliar salidas de Web Service API de agencias de carga, y rastrear diferencias de rentabilidad y asignación de costos a nivel SKU hasta su lógica contable real.</p>**

> **Prueba la calculadora gratuita de costo landed basada en web. Si necesitas la versión Excel sin conexión para tus registros permanentes, pistas de auditoría y uso mensual repetido, puedes comprarla con una garantía de devolución de dinero de 30 días, sin preguntas.**
> 
> [🌐 Prueba la Calculadora Gratuita de Costo Landed en el Navegador](https://hyvoid.github.io/landed-cost-calculator-excel/)
> 
> [📥 Descarga la Plantilla Excel de Costo Landed Sin Conexión](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator)


## Puntos de Dolor Comunes de Cadena de Suministro y Soluciones de Costo Landed

En lugar de simplemente rastrear números, este kit mapea tus problemas logísticos de importación más frustrantes a soluciones analíticas estructuradas:

* **Punto de Dolor: Discrepancias poco claras de API de 3PL.** 
  **Solución: Acuerdo de costo landed a nivel de envío** — verifica al instante si el Web Service de tu agente llega al mismo Costo de Bienes Vendidos (COGS) total que una referencia profesional independiente.
* **Punto de Dolor: Erosión de margen oculta por tarifas de importación.** 
  **Solución: Diagnóstico de varianza por categoría de costo** — localiza exactamente dónde divergen el flete, el arancel aduanero, la manipulación portuaria, el seguro marítimo u otros grupos de costos operativos.
* **Punto de Dolor: Rentabilidad de producto distorsionada.** 
  **Solución: Rastreo de costo landed a nivel de SKU** — identifica qué productos específicos soportan costos de valoración de inventario materialmente diferentes bajo métodos de cálculo distintos.
* **Punto de Dolor: Distribución de costos logísticos defectuosa.** 
  **Solución: Análisis de impacto de base de asignación** — descubre si las discrepancias se originan al asignar por peso bruto, volumen cúbico (CBM), valor comercial, valor aduanero FOB o unidades de cantidad.
* **Punto de Dolor: Decisiones de precios inexactas.** 
  **Solución: Revisión de impacto de economía por unidad** — visualiza cómo las diferencias de asignación de cadena de suministro cambian directamente el costo landed unitario y tu multiplicador de costo landed general.
* **Punto de Dolor: Fatiga de auditoría y cumplimiento.** 
  **Solución: Marcado de severidad de excepciones** — clasifica automáticamente si una varianza de factura está dentro de la tolerancia contable, requiere revisión manual, o representa un problema crítico de cálculo ERP.

## Tutorial Paso a Paso de Reconciliación de Costo Landed (Guía de Inicio Rápido)

Sigue este flujo de trabajo para auditar tus facturas de flete y validar costos unitarios eficientemente:

1. **Paso 1: Configura los Parámetros de Importación y Envío.**
   Define el Case ID, Shipment ID, moneda base de reporte, política contable de inventario (p. ej., ASC 330), tasas de Cambio de Divisas (FX) y umbrales de varianza absoluta/porcentual aceptables en la hoja dedicada `00_SETUP_PARAMS`.

2. **Paso 2: Carga Facturas Comerciales y Datos de Cadena de Suministro.**
   Pega tus datos estructurados de envío y costos en las hojas de entrada designadas. Puedes consolidar Facturas Comerciales, Listas de Empaque, Órdenes de Compra (POs), formularios de Entrada Aduanera (p. ej., CBP Form 7501) y facturas de flete 3PL directamente desde tus exportaciones ERP.

3. **Paso 3: Ejecuta el Análisis de Rentabilidad a Nivel de SKU.**
   Haz clic para obtener resultados al instante. La referencia profesional calcula el costo landed a nivel de SKU basándose en tus entradas de envío reales y grupos de gastos. El kit compara automáticamente tus resultados del Web Service API contra esta referencia a nivel de envío, categoría y SKU.

4. **Paso 4: Audita Varianzas y Mantén Actualizaciones Periódicas.**
   Carga nuevos casos de prueba sin romper la arquitectura de cálculo subyacente. Actualiza tus datos fuente, refresca la comparación del panel y dedica tiempo solo a revisar las varianzas de factura específicas que activan una alerta de tolerancia.

5. **Paso 5: Estandariza tu Flujo de Trabajo.**
   👉 **¿Listo para auditar envíos a escala?** No empieces desde cero cada vez. [📥 Descarga la Plantilla Excel Reutilizable de Costo Landed](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator) para guardar de forma segura tus datos históricos de reconciliación, automatizar tus auditorías mensuales de flete y estandarizar la metodología de asignación de costos de tu empresa.

## Por Qué Construí Esta Herramienta de Asignación de Costos

Un cálculo de costo landed puede producir un número que parece razonable en tu ERP mientras aún usa una lógica de asignación fundamentalmente incorrecta.

Eso se vuelve especialmente peligroso para la valoración de inventario cuando un envío consolidado contiene muchos SKUs y costos logísticos compartidos. El flete marítimo, la demora portuaria, la corretaje aduanero, el seguro y los aranceles requieren tratamientos contables diferentes. Un Web Service SaaS genérico podría devolver un resultado limpio a nivel de SKU, pero una UI limpia no prueba que el método de asignación subyacente sea legal o financieramente apropiado.

La falla usualmente no es aritmética. Es **opacidad de método**.

Si un panel de cadena de suministro reporta que el SKU A tiene un costo landed de $14.82, la pregunta importante no es simplemente si $14.82 puede reproducirse. La pregunta importante es **por qué se produjo ese número**.

Este kit crea una referencia profesional independiente para que los dos cálculos de costeo puedan compararse contra exactamente el mismo envío importado.

Por ejemplo, supón que un envío de contenedor mixto tiene 1,000 unidades a través de múltiples SKUs. El Web Service automatizado asigna el flete según *valor comercial*, mientras que la referencia profesional asigna exactamente el mismo grupo de flete por *peso bruto*. El total del envío coincide perfectamente, sin embargo, el COGS individual por SKU y los márgenes de ganancia fluctuarán salvajemente.

Antes de usar este marco de reconciliación:

> "Los números del ERP son diferentes de la factura de flete."

Después de usar este marco de reconciliación:

> "El costo total del envío coincide, pero la asignación de flete a nivel de SKU difiere porque la API del 3PL usa Valor Comercial mientras que nuestra política interna dicta asignación por Peso Bruto."

Esa distinción transforma la revisión financiera de **buscar manualmente un número que no coincide** a **identificar el mecanismo de negocio específico que causó la erosión del margen**.

## ¿Por Qué Usar una Herramienta de Costo Landed Dedicada Sobre Hojas de Cálculo Básicas?

| Desafío de Reconciliación de Cadena de Suministro | Enfoque Tradicional con Hoja Manual | Solución de Plantilla de Costo Landed Automatizada |
| :--- | :--- | :--- |
| **Rastreo de Asignación de Costos Compartidos 3PL** | Dependes de un Web Service de caja negra para producir costos de SKU; la base exacta de asignación (Peso vs. Valor) es imposible de auditar independientemente. | Una referencia profesional independiente define claramente la base de asignación, haciendo tus cálculos de COGS totalmente explícitos y comparables. |
| **Errores de Rentabilidad Enmascarados a Nivel de SKU** | Un total general coincidente en la factura de flete oculta destrucción material del margen a nivel unitario. | La reconciliación de facturas se desacopla en niveles de Envío, Categoría y SKU para asegurar exactitud total. |
| **Varianzas de Valoración de Inventario Inexplicables** | Los revisores financieros ven una brecha sin saber si proviene de asignación de flete, reglas de impuesto de importación, tasas FX o incoterms CIF/FOB. | Las varianzas se clasifican al instante en categorías diagnósticas estructuradas de causa raíz para el equipo contable. |
| **Discrepancias de Facturas en Moneda Extranjera (FX)** | Suposiciones manuales de conversión diaria introducen brechas de reconciliación acumulativas a través de órdenes de compra internacionales. | Las tasas FX se mantienen en un repositorio central y se aplican consistentemente en toda la referencia de cadena de suministro. |
| **Tolerancias de Auditoría de Flete Inconsistentes** | Los empleados de AP adivinan manualmente si una discrepancia de factura es lo "suficientemente material" para investigar. | Umbrales de tolerancia absolutos ($) y porcentuales (%) configurables hacen cumplir una política corporativa estandarizada de revisión. |
| **Inventario Capitalizado vs. Gastos de Período** | Los contadores mezclan accidentalmente costos de inventario capitalizados con gastos operativos inmediatos. | Los asientos de costo exigen una etiqueta de tratamiento contable explícito (p. ej., capitalizar vs. gastar) conforme a políticas estándar. |

## ¿Quién Necesita Este Software y Plantilla Excel de Costo Landed?

Este kit está diseñado específicamente para capturar casos límite que las calculadoras genéricas pasan por alto. Está construido a propósito para:

* **Gerentes de Operaciones de E-commerce e Importadores:** Necesitan una *plantilla de costo landed para Shopify/Amazon FBA* para proteger los márgenes de producto de tarifas ocultas de reenvío.
* **Controladores de Cadena de Suministro y Logística:** Necesitan una *solución de software de auditoría de flete* para impugnar facturas 3PL inexactas y salidas de Web Service API.
* **Contadores de Costos y Analistas Financieros:** Necesitan una *calculadora de arancel de importación y Excel de reconciliación* para asegurar que la valoración de inventario cumpla con GAAP/ASC 330.
* **Equipos de Adquisiciones y Producto:** Necesitan una *herramienta de modelado de economía por unidad* para pronosticar los costos reales de abastecimiento antes de emitir Órdenes de Compra internacionales.

Es particularmente útil cuando el envío marítimo/aéreo subyacente contiene múltiples SKUs y costos logísticos compartidos, y tu objetivo es probar si un cálculo empresarial existente es meramente "diferente" o "financieramente incorrecto".

*(Nota: Aunque poderosa para analítica y auditoría, este es un módulo de apoyo a la decisión y **no** está destinado a reemplazar por completo tu ERP de producción, libro contable NetSuite o sistema empresarial de Cumplimiento Comercial).*

## Acerca del Creador

Construyo rastreadores ligeros, herramientas de auditoría de flete y arquitecturas de apoyo a la decisión para operaciones que tienen demasiadas piezas en movimiento para mantener en la cabeza.

La pregunta central es simple: **¿Qué datos precisos de cadena de suministro necesitan estar en un solo panel para tomar la próxima decisión de adquisición con confianza?**

El Kit de Referencia de Cálculo de Costo Landed y Reconciliación es una implementación concreta de esa filosofía. En lugar de construir solo otra calculadora genérica de flete, empaqueta el razonamiento profesional necesario para referenciar, reconciliar y auditar de forma independiente resultados complejos de costo landed.

## Detalles Técnicos y Arquitectura

<details>
<summary>Para Revisores Técnicos, Integradores de ERP y Practicantes de Excel</summary>

### Flujo de Datos del Sistema y Arquitectura del Libro de Trabajo

El libro de trabajo hace cumplir estrictamente un flujo de datos unidireccional para mantener la integridad de auditoría:

```text
Commercial Invoices
3PL Freight Bills
Customs Form 7501
Purchase Orders (POs)
        │
        ▼
┌──────────────────────────┐
│ 00_SETUP_PARAMS          │
│ Global parameters        │
│ FX / tolerance / policy  │
└────────────┬─────────────┘
             │
       ┌─────┴─────┐
       ▼           ▼
┌─────────────┐ ┌─────────────────┐
│ 01_SKU_     │ │ 02_COST_POOL_   │
│ MASTER_INPUT│ │ INPUT           │
│ Shipment/SKU│ │ External costs  │
└──────┬──────┘ └────────┬────────┘
       │                 │
       └────────┬────────┘
                ▼
     ┌──────────────────────┐
     │ 03_PRACTITIONER_CALC │
     │ Independent benchmark│
     └──────────┬───────────┘
                │
        ┌───────┴────────┐
        ▼                ▼
┌────────────────┐ ┌───────────────────┐
│ 04_WEBSERVICE_ │ │ 05_VARIANCE_      │
│ RECON          │ │ DIAGNOSIS         │
│ Multi-level    │ │ Root-cause review │
│ reconciliation │ │                   │
└───────┬────────┘ └─────────┬─────────┘
        │                    │
        └──────────┬─────────┘
                   ▼
        ┌─────────────────────┐
        │ 06_EXECUTIVE_SUMMARY│
        │ Review / audit view │
        └─────────────────────┘

```

| Hoja de Base de Datos | Tipo de Capa | Rol Analítico |
| --- | --- | --- |
| `00_SETUP_PARAMS` | Parámetro / Supuesto | Control central para Case ID, Shipment ID, moneda base, tasas FX, política contable GAAP, diccionario de base de asignación y tolerancias de auditoría. |
| `01_SKU_MASTER_INPUT` | Entrada de Datos | Ingestión estructurada de datos de envío y SKU desde POs, Facturas Comerciales, Listas de Empaque y documentos aduaneros. |
| `02_COST_POOL_INPUT` | Entrada de Datos | Grupos de gastos externos incluyendo flete marítimo/aéreo, aranceles, manipulación portuaria, seguro marítimo, corretaje aduanero y desembolsos misceláneos. |
| `03_PRACTITIONER_CALC` | Cálculo de Referencia | Ejecución independiente de costo landed del practicante utilizando la base de asignación estricta mapeada a cada ítem de costo específico. |
| `04_WEBSERVICE_RECON` | Reconciliación | Comparación directa de varianza de la referencia profesional contra la salida del Web Service API a niveles de envío, categoría y SKU. |
| `05_VARIANCE_DIAGNOSIS` | Atribución de Causa Raíz | Auditoría estructurada de discrepancias materiales y clasificación de sus probables causas raíz sistémicas (p. ej., deslizamiento FX vs. mala asignación de Peso). |
| `06_EXECUTIVE_SUMMARY` | Presentación / Reporte | Panel consolidado que muestra tasas de coincidencia a nivel de caso, varianza financiera neta, desviaciones mayores de margen y distribución diagnóstica. |

La arquitectura separa deliberadamente **entradas, cálculo, reconciliación, diagnóstico y presentación**. Los parámetros se mantienen centralmente en una hoja de estado dedicada en lugar de estar peligrosamente codificados en fórmulas de celdas posteriores.

El esquema registrado cubre parámetros de caso, atributos de SKU, metadatos de grupos de costo y cargas útiles de Web Service. Las salidas clave calculadas de referencia incluyen: valor comercial total, peso bruto (KG/LBS), peso volumétrico (CBM), valor aduanero, flete asignado, arancel asignado, overhead capitalizado, costo landed total, costo landed unitario y el crucial multiplicador de costo landed.

### Tres Trampas Comunes de Costeo Que Atrapan Incluso a Practicantes Experimentados de Cadena de Suministro

#### Trampa 1 — Un Total de Envío Coincidente Oculta una Asignación de Costo por SKU Defectuosa

**1. Se tomó una decisión:**
Se aprueba un Web Service 3PL porque su costo landed total para todo el contenedor coincide con el total de la factura de envío calculado independientemente.

**2. El supuesto oculto defectuoso:**
La reconciliación se realizó exclusivamente a nivel de agregado de envío. El flete compartido fue asignado mediante una metodología diferente entre los dos sistemas, pero el total absoluto del grupo de flete permaneció estático.

**3. El impacto en operaciones:**
El total del contenedor parece totalmente conciliado, enmascarando el caos interno:

| Métrica | Referencia Profesional | Web Service 3PL |
| --- | --- | --- |
| Grupo total de flete | $10,000 | $10,000 |
| Costo landed total | $60,000 | $60,000 |
| **Costo landed SKU A** | **$18.00/unidad** | **$16.40/unidad** |
| **Costo landed SKU B** | **$42.00/unidad** | **$45.20/unidad** |

El resultado macro dice **MATCH**. La micro economía unitaria por SKU (y la estrategia de precios subsecuente) están completamente distorsionadas.

**4. El enfoque de reconciliación corregido:**
Reconcilia secuencialmente para preservar la integridad del margen:
`Total de envío` → `Grupo de categoría de costo` → `Lógica de asignación por SKU` → `Costo landed unitario`

**5. Resultado diagnóstico corregido:**

> **"El total del envío se concilia, pero la asignación de flete a nivel de SKU requiere revisión operativa inmediata."**
> El problema se aísla puramente a la lógica de asignación en lugar de rechazar falsamente toda la integración del Web Service.

#### Trampa 2 — Una Pequeña Diferencia en Dólares Representa una Varianza Porcentual Masiva

**1. El proceso de revisión defectuoso:**
Un empleado de AP descarta una varianza de factura porque la diferencia absoluta es "solo unos pocos dólares".

**2. El fallo de contexto:**
Una varianza de $3 conlleva implicaciones de margen vastly diferentes dependiendo del costo unitario base:

| Costo Unitario de Referencia | Varianza Absoluta | Impacto de Varianza Porcentual |
| --- | --- | --- |
| $1,000 | $3 | 0.30% (Despreciable) |
| $100 | $3 | 3.00% (Notable) |
| **$20** | **$3** | **15.00% (Amenaza Crítica de Margen)** |

**3. La solución automatizada:**
Esta herramienta hace cumplir una lógica de umbral dual que exige que tanto `TOLERANCE_ABS` como `TOLERANCE_PCT` pasen simultáneamente antes de conceder un estado de `MATCH`.

#### Trampa 3 — La Discrepancia Proviente de la "Base", No de Mala Aritmética

**1. El mal diagnóstico:**
Cuando un resultado del Web Service no coincide con la referencia interna, los revisores asumen al instante un error matemático o una errata de entrada de datos.

**2. La realidad estructural:**
Los cálculos son matemáticamente perfectos, pero los sistemas están usando bases de asignación fundamentalmente incompatibles:

| Base de Asignación de Costos | Medida de SKU Dependiente |
| --- | --- |
| **Peso Bruto** | Peso bruto físico total |
| **Volumen (Peso Dimensional)** | Metros cúbicos totales (CBM) |
| **Valor Comercial** | Valor total de factura de compra |
| **Valor Aduanero** | Valor total gravable declarado |
| **Unidades de Cantidad** | Recuento total de artículos |

Asignar una factura de flete marítimo de $5,000 por **Peso Bruto** produce un COGS por SKU drásticamente diferente que asignar exactamente la misma factura por **Valor Comercial**.

**3. La conclusión diagnóstica:**
En lugar de una vaga *"El cálculo de la API está mal"*, esta plantilla genera un registro de auditoría procesable:

> **"Varianza atribuida a desajuste de base de asignación: el 3PL utilizó Peso Bruto vs. Política Interna utilizando Valor Comercial."**

</details>

---

## La Lógica de Negocio y Metodología

### El Problema de Negocio Central

La mayoría de las redes de cadena de suministro y sistemas ERP empresariales tratan el costo landed como un simple ejercicio aritmético — tomar una factura de flete consolidada y dividirla entre las unidades importadas. Sin embargo, el costo landed es fundamentalmente una **decisión estratégica de contabilidad de costos**.

Cuando las APIs de logística de terceros (3PL) o plataformas SaaS de caja negra producen un costo final por SKU, ocultan la lógica de asignación subyacente. Si artículos pesados de bajo valor comparten un contenedor de envío con artículos ligeros de alto valor, aplicar la base de asignación incorrecta (p. ej., distribuir el flete marítimo por Valor Comercial en lugar de Volumen/CBM) distorsiona severamente tu economía por unidad. Esta opacidad de método lleva a bienes pesados subvalorados, bienes ligeros sobrevalorados, y una erosión de margen sistémica que la auditoría tradicional de facturas no puede detectar.

### La Metodología del Practicante

Este kit reemplaza el modelo de "confianza en caja negra" con un **marco de Costeo Basado en Actividades (ABC) y Reconciliación Multinivel**.

La metodología se ejecuta a través de tres fases lógicas para asegurar el cumplimiento financiero y una valoración de inventario precisa:

1. **Mapeo Desacoplado de Impulsores de Costo (El Motor de Reglas):** 
   En lugar de aplicar un multiplicador porcentual plano a todos los bienes, el kit exige que cada grupo de costos externo se mapee explícitamente a su verdadero impulsor físico o financiero. 
   * *El Flete Marítimo y Aéreo* es impulsado por el consumo espacial (Volumen/CBM o Peso Dimensional).
   * *El Transporte Terrestre* es impulsado por restricciones de carga útil (Peso Bruto).
   * *Los Aranceles y Tarifas* son impulsados por evaluaciones fiscales legales (Valor Aduanero / FOB).
   * *El Seguro Marítimo* es impulsado por la exposición a riesgo financiero (Valor Comercial).
   
2. **Cálculo Sombrío Independiente (La Referencia):** 
   Antes de aceptar los números de una API externa en tu ERP, el libro de trabajo genera una referencia "sombría" localizada. Calcula lo que el Costo de Bienes Vendidos (COGS) a nivel de SKU *debería* ser, adhiriéndose estrictamente a las políticas contables declaradas de tu empresa (p. ej., GAAP / ASC 330 / IAS 2).

3. **Diagnóstico de Varianza en Tres Niveles (La Auditoría):**
   El sistema no simplemente verifica si el total general coincide con la factura. Fuerza una reconciliación en tres niveles organizacionales distintos:
   * **Macro (Nivel de Envío):** ¿El flujo de caja agregado coincide con la factura de flete?
   * **Meso (Nivel de Categoría):** ¿El agente evaluó con precisión el arancel vs. flete vs. manipulación, o los costos se están desangrando a través de categorías?
   * **Micro (Nivel de SKU):** ¿Se le cargó a un producto específico una proporción desproporcionada del costo logístico, destruyendo así su margen bruto?

### El Resultado Estratégico

Al desplazar el enfoque de la *verificación aritmética* (¿coinciden los números?) a la *auditoría metodológica* (¿se aplicó la regla de negocio correcta?), los equipos de finanzas y operaciones recuperan el control sobre sus datos de cadena de suministro. Esta lógica asegura que las estrategias de precios al consumidor y los análisis de margen se basen en la verdadera carga económica de importar un producto, en lugar de un promedio generalizado.

---

## Explora Más Kits de Herramientas Financieras y de Operaciones

* **Kits de Herramientas de Construcción y Operaciones** — Controles basados en Excel para rastreo de costos de proyecto, pronóstico de rentabilidad y flujos de trabajo operativos en obra.
* **Kits de Herramientas de Inventario y Reconciliación** — Modelos prácticos para visibilidad de inventario WMS, reconciliación de conteo cíclico y análisis de merma/pérdida.
* **Kits de Herramientas de Rentabilidad y Costeo** — Marcos analíticos productizados para costeo de trabajos de manufactura, economía unitaria de e-commerce y análisis profundo de margen.

Explora la colección más amplia de plantillas de cadena de suministro a través del perfil GitHub del proyecto o la página oficial de distribución.

## Licencia y Uso

Este proyecto de arquitectura de software y plantilla se publica bajo la **Licencia Apache 2.0**.

Usa, modifica y redistribuye este kit de costo landed dentro de tus proyectos empresariales o personales de acuerdo con los términos estándar de la Licencia Apache 2.0.
