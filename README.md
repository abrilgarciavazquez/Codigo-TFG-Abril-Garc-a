# Proyecto TFG: Modelado y Simulación de Baterías Sólidas

Este trabajo de fin de grado se centra en la modelización y simulación de baterías de estado sólido, combinando métodos estadísticos y modelos electroquímicos avanzados basados en datos experimentales extraídos de la literatura científica.

## Estructura del proyecto

### 1. Generación del dataset

Se ha elaborado un dataset estructurado en formato CSV que integra parámetros físicos, químicos y electroquímicos relevantes para baterías sólidas. Los datos han sido recopilados y procesados a partir de múltiples fuentes bibliográficas, garantizando la coherencia y calidad necesaria para su uso en modelos numéricos posteriores.

### 2. Modelado Monte Carlo

Se implementa un modelo Monte Carlo estocástico para simular la distribución espacial y temporal de la concentración de iones de litio y la cantidad molar de los materiales constituyentes. Este enfoque probabilístico permite capturar la heterogeneidad y la incertidumbre inherente a los procesos de transporte y reacción dentro del electrolito sólido.

### 3. Modelo Doyle-Fuller-Newman (DFN)

Se desarrolla y emplea un modelo electroquímico DFN para describir la cinética de carga y descarga de la batería, incluyendo la difusión de especies en los electrodos, las reacciones electroquímicas en las interfaces y la distribución del potencial eléctrico. Este modelo permite analizar el comportamiento dinámico bajo diferentes condiciones de operación.

### 4. Modelo Poisson-Nernst-Planck (PNP)

Se implementa el modelo PNP para resolver la distribución del potencial eléctrico y el transporte iónico en el electrolito sólido, considerando la interacción entre campos eléctricos y gradientes de concentración. Este modelo es fundamental para entender la física del transporte en baterías de estado sólido a nivel microscópico.

---

## Contenidos del repositorio

- Dataset en formato CSV con los parámetros recopilados.  
- Código fuente de los modelos Monte Carlo, DFN y PNP implementados.  
- Documentación y resultados de las simulaciones.

---

Este proyecto proporciona una plataforma integral para el estudio y optimización de baterías sólidas, integrando datos experimentales con técnicas computacionales avanzadas.

