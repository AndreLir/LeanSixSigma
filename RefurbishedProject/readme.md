Perfecto 🚀, aquí tienes un **README.md** completo y profesional en **Markdown** para tu proyecto, estructurado tal como suele hacerse en GitHub:

---

# 🏭 Proyecto Lean Six Sigma – Optimización de Proceso de Remodelación de Equipos

![Lean Six Sigma](https://img.shields.io/badge/Lean-Six%20Sigma-green)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Descripción

Este proyecto aplica la metodología **Lean Six Sigma (DMAIC)** al proceso de **remodelación y validación de equipos tecnológicos**.
El objetivo principal fue **reducir tiempos de ciclo y eliminar sobreprocesos** que no generaban valor, especialmente en la validación de series y el registro inicial.

A través del análisis de capacidad del proceso (**Cp, Cpk**) y la simulación de datos en Python, se identificaron las principales ineficiencias y se implementaron mejoras que permitieron:

* Reducir **tiempos de Recepción y Almacenado** de 27–36h a 6–7h.
* Optimizar actividades de **Limpieza, Testeo y Encajado** con mayor control de variabilidad.
* Implementar **automatización en impresión de series** y **reportes digitales al cliente**.

---

## 🎯 Objetivos del Proyecto

* Eliminar **sobreprocesos innecesarios**.
* Mejorar la **capacidad del proceso** (Cpk).
* Reducir tiempos de ciclo en más del **30%**.
* Asegurar la **trazabilidad de equipos** de forma digital y confiable.

---

## 🧩 Metodología (DMAIC)

1. **Definir:** Identificación de problemas y VOC (Voz del Cliente).
2. **Medir:** Recolección de datos históricos y simulación de 200 → 40 registros.
3. **Analizar:** Identificación de causas raíz con **5 Porqués**.
4. **Mejorar:** Implementación de soluciones (automatización, digitalización, capacitación).
5. **Controlar:** Evaluación de **Cp y Cpk** para validar estabilidad del proceso.

---

## 📊 Resultados Clave

| Proceso             | Antes (Cpk) | Después (Cpk)                              | Mejora                    |
| ------------------- | ----------- | ------------------------------------------ | ------------------------- |
| TC\_Horas\_RyA      | 0.94        | 0.80\* (pero con gran reducción de tiempo) | ✅ Mayor impacto en tiempo |
| TC\_Horas\_Limpieza | -0.35       | 0.76                                       | ✅ Estabilidad alcanzada   |
| TC\_Horas\_Test     | -0.49       | 0.71                                       | ✅ Estabilidad alcanzada   |
| TC\_Horas\_Encajado | -0.36       | 0.64                                       | ✅ Estabilidad alcanzada   |

\* Aunque el **Cpk de RyA** se redujo levemente, la mejora en **tiempo absoluto** fue la más significativa: de 27–36h a solo 6–7h.

---

## 🛠️ Tecnologías Utilizadas

* **Python** (Pandas, NumPy, SciPy, Matplotlib).
* **Power BI** (reportes digitales automáticos al cliente).
* **Lean Six Sigma** (DMAIC, 5 Porqués, análisis de desperdicios).

---

## 📂 Estructura del Repositorio

```
├── data/                     # Dataset de simulación
│   └── dataset_modems_40.csv
├── notebooks/                # Jupyter notebooks con análisis
│   └── process_capability.ipynb
├── reports/                  # Resultados y reportes generados
│   └── Capability_Analysis.pdf
├── src/                      # Scripts de Python
│   └── capability_analysis.py
└── README.md                 # Este archivo
```

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/usuario/proyecto-lean-six-sigma.git
   cd proyecto-lean-six-sigma
   ```
2. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar el análisis de capacidad:

   ```bash
   python src/capability_analysis.py
   ```

---

## 📈 Conclusión

Este proyecto demuestra cómo la combinación de **Lean Six Sigma + Ciencia de Datos** puede lograr mejoras significativas:

* Procesos más rápidos.
* Menor variabilidad.
* Mayor trazabilidad y satisfacción del cliente.

---

## 👤 Autor

**Andres Ortiz** – Ingeniero Industrial | Lean Six Sigma | Data & Analytics


---
