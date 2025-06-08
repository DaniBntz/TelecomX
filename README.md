# 📊 TelecomX Challenge - Análisis de Cancelación de Clientes (Churn)

Este proyecto tiene como objetivo analizar y entender las causas detrás de la **cancelación de clientes** en una compañía de telecomunicaciones, utilizando técnicas de análisis de datos y visualización. A través de este análisis, se busca identificar **patrones de comportamiento** que permitan reducir la pérdida de clientes y mejorar la fidelización.

---
## 🧰 Herramientas Utilizadas

- `Python`
- `Pandas` y `NumPy` para manipulación de datos
- `Seaborn` y `Matplotlib` para visualización
- `Google Colab` como entorno de desarrollo
- `GitHub` y `Markdown` para documentación

---

## 📌 Objetivos

- Analizar la tasa de cancelación de clientes y sus posibles causas.
- Identificar relaciones entre variables demográficas, contractuales y financieras.
- Detectar perfiles de clientes con mayor riesgo de cancelación.
- Proporcionar recomendaciones para mitigar el churn.

---

## 📊 Resultados Clave

- Los clientes con **contratos mensuales** presentan una mayor probabilidad de cancelar el servicio.
 <p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/grafico_tipo_contrato.png?raw=true" alt="Tipos de contrato" width="600"/>
</p>

- El uso de **cheque electrónico** como método de pago se asocia con mayor churn.
<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/grafico_metodos_de_pago.png?raw=true" alt="Métodos de pago" width="600"/>
</p>

- **Menor tiempo de permanencia** y **menor gasto acumulado** son comunes entre quienes cancelan.

  Esto sucede porque desde luego, se van antes por ello el gasto total es menor.
<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/grafico_cuentas_tiempo.png?raw=true" alt="Tiempo de permanencia y gastos" width="600"/>
</p>

- **Mayor gasto mensual** y **menor tiempo de permanencia**, asociados con la cancelación.

  Esto sugiere que, aunque no cancelan inmediatamente, los usuarios con tarifas elevadas y poca fidelización terminan abandonando el servicio en menos de un año.
<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/comparacion_pago_mes_dia_y_tiempo.png?raw=true" alt="Tiempo de permanencia y gastos" width="800"/>
</p>  

- Los clientes que usan **fibra óptica** tienden a cancelar más que los que usan **DSL**.
<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/tipos_de_servicio.png?raw=true" alt="Tipos de servicio" width="600"/>
</p>

- Ciertas combinaciones de características permiten **predecir con mayor precisión** el riesgo de cancelación.

<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/top_correlacion_cancelacion.png?raw=true" alt="correlaciones de cancelación" width="600"/>
</p>

- Tipos de clientes: **Edad, género y dependientes a cargo**.
  
<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/clientes_jubilados.png?raw=true" alt="Clientes jubilados" width="600"/>
</p>

<p align="left">
  <img src="https://github.com/DaniBntz/TelecomX/blob/main/imagenes/genero_y_dependencia.png?raw=true" alt="Género y dependientes a cargo" width="600"/>
</p>

---

## **Recomendaciones**

✅ Fomentar la transición hacia contratos de mayor duración mediante promociones o beneficios exclusivos.

✅ Incentivar el uso de métodos de pago automáticos, ya que se asocian a menor churn.

✅ Monitorear activamente a los clientes con alto coste diario o mensual, ya que presentan mayor riesgo de cancelación.

✅ Implementar beneficios de permanencia o reducción gradual de tarifas como incentivo para prolongar la relación contractual.

✅ Rediseñar los planes con fibra óptica para ofrecer mayor valor o soporte, ya que esta tecnología está asociada con mayor tasa de cancelación.

✅ Segmentar a los clientes con más riesgo de fuga para aplicar estrategias de retención personalizadas.

✅ Implementar alertas tempranas cuando un cliente cumple patrones de alto riesgo de churn.

---

## ✍️ Autor

**Creador del proyecto:** J.Daniela Benitez  

---
