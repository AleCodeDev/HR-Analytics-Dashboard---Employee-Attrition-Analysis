**📊 HR Analytics Dashboard - Employee Attrition Analysis**

# **🎯 Resumen Ejecutivo<br>**
Dashboard interactivo de análisis de recursos humanos que identifica patrones de rotación de personal y factores de riesgo en una empresa con 1,470 empleados. El proyecto revela que el 16.12% de attrition está concentrado en perfiles específicos: empleados jóvenes, solteros, en roles de ventas, y con baja antigüedad.
---
**🚀 Problema de Negocio<br>**
Una empresa enfrenta una tasa de rotación de personal del 16.12% (237 empleados renunciaron), significativamente por encima del estándar saludable de 5-10%. Se necesita identificar:

- ¿Qué departamentos y roles tienen mayor attrition?<br>
- ¿Qué factores predicen que un empleado renunciará?<br>
- ¿Cuál es el perfil de riesgo alto?<br>
- ¿Cómo se relacionan salarios, distancia y satisfacción con las renuncias?

**📊 Solución Implementada<br>**
Dashboard interactivo de 3 páginas en Power BI que analiza:

**Página 1: Executive Overview**

KPIs principales: Total empleados, attrition count, attrition rate, edad promedio, salario promedio<br>
Distribución de attrition por departamento y género<br>
Tarjeta de alerta: 23 empleados en alto riesgo de renuncia

**Página 2: Attrition Deep Dive - Root Cause Analysis**

Análisis comparativo: años en la empresa, distancia de casa, satisfacción laboral<br>
Attrition por rol de trabajo (matriz con tasas y salarios)<br>
Identificación de roles críticos: Sales Representative (39.76% attrition)<br>

**Página 3: Employee Demographics & Profile Analysis**

Distribución demográfica: edad, género, estado civil, campo educativo<br>
Análisis generacional: empleados jóvenes vs senior<br>
Comparación de edad promedio: activos (38 años) vs renuncias (34 años)

**🔍 Insights Principales<br>**
**📈 Hallazgos Críticos:**

**Roles de Alto Riesgo:**

- Sales Representative: 39.76% attrition (crítico)<br>
- Laboratory Technician: 23.94% attrition<br>
- Human Resources: 23.08% attrition

**Perfil de Riesgo:**

- **Edad:** 4 años más jóvenes (34 vs 38 años)<br>
- **Estado civil:** Solteros (120 renuncias - el grupo más alto)<br>
- **Antigüedad:** 2.24 años menos en la empresa (5.13 vs 7.37 años)<br>
- **Distancia:** Viven 1.44 km más lejos (10.63 vs 9.19 km)

**Brecha Salarial:**

- Empleados que renunciaron: $4,787/mes promedio<br>
- Empleados activos: $6,833/mes promedio<br>
- Gap: $2,046/mes - El salario bajo es un factor significativo

**Alto Riesgo Actual:**

- **23** empleados activos cumplen criterios de alto riesgo<br>
- **Criterios:** JobSatisfaction ≤ 2 + YearsAtCompany ≤ 2

**📊 Distribución:**

- **Research & Development:** 65.37% de empleados, 133 renuncias<br>
- **Sales:** 30.34% de empleados, 92 renuncias<br>
- **Human Resources:** 4.29% de empleados, 12 renuncias

**💡 Recomendaciones de Negocio**
**Acciones Inmediatas:**

**Intervención en Sales Representative:**

- Revisar estructura de compensación (están $1,400 bajo el promedio)<br>
- Implementar plan de retención para este rol<br>
- Análisis de carga de trabajo y expectativas

**Programa de Retención para Empleados Jóvenes:**

- Mentorías para empleados menores de 35 años<br>
- Plan de carrera claro en primeros 2 años<br>
- Revisión salarial para nuevos ingresos

**Revisión de Compensación:**

- Ajustar salarios del cuartil inferior<br>
- Bonus de retención para roles críticos<br>
- Benchmark contra mercado

**Seguimiento de Empleados de Alto Riesgo:**

- Entrevistas one-on-one con los 23 en riesgo<br>
- Plan de mejora de satisfacción laboral<br>
- Considerar trabajo remoto para empleados lejanos

**🛠️ Herramientas y Técnicas Utilizadas Power BI:**

- **Power Query:** Limpieza y transformación de datos<br>
- **DAX:** 20+ medidas calculadas (básicas, intermedias y avanzadas)<br>
- **Modelado de datos:** Tabla de hechos + dimensiones<br>
- **Visualizaciones:** 15+ visuales interactivos<br>
- Slicers sincronizados para interactividad

**Funciones DAX:**

- CALCULATE, FILTER, ALL<br>
- DIVIDE (manejo de errores)<br>
- TOPN (análisis de rankings)<br>
- Variables (VAR/RETURN) para código limpio<br>
- Time Intelligence (comparaciones temporales)<br>
- Formato condicional con medidas

**Diseño:**

- Paleta de colores consistente<br>
- Iconos en KPIs para mejor comprensión visual<br>
- Formato condicional (semáforos de riesgo)<br>
 -Tooltips informativos<br>
- Navegación intuitiva entre páginas

**📈 Habilidades Demostradas<br>**
**✅ Análisis de Datos:**

- Identificación de patrones y correlaciones<br>
- Segmentación de datos (edad, departamento, rol)<br>
- Análisis comparativo (activos vs renuncias)<br>
- Identificación de outliers y grupos de riesgo

**✅ Power BI Técnico:**

- Limpieza de datos en Power Query<br>
- Creación de columnas calculadas (Age Groups)<br>
- 20+ medidas DAX con diferentes complejidades<br>
- Formato condicional dinámico<br>
- Interactividad con slicers

**✅ Business Intelligence:**

- Traducción de datos a insights accionables<br>
- Storytelling con datos (3 páginas con narrativa clara)<br>
- KPIs relevantes para stakeholders<br>
- Recomendaciones basadas en datos

**✅ Visualización:**

- Selección apropiada de gráficos por tipo de dato<br>
- Diseño limpio y profesional<br>
- Uso de colores para comunicar (rojo=problema, verde=ok)<br>
- Iconografía para facilitar comprensión

**📁 Dataset**
**Fuente:** IBM HR Analytics Employee Attrition Dataset (Kaggle)<br>

**Características:**
- 1,470 registros (empleados)<br>
- 35 columnas<br>

**Variables:** demográficas, laborales, satisfacción, compensación

**Transformaciones aplicadas:**

- Eliminación de columnas redundantes (Over18, EmployeeCount)<br>
- Creación de grupos de edad (5 categorías)<br>
- Validación de tipos de datos<br>
- Limpieza de valores nulos

**🎯 Resultados del Proyecto<br>**
Impacto Potencial:<br>
**Si la empresa implementa las recomendaciones:**

- Reducción proyectada de attrition: de 16.12% a 10% (ahorro de ~60 renuncias/año)<br>
- Ahorro estimado en reclutamiento: $50K-$100K/año<br>
- Mejora en clima laboral y productividad

**Métricas de Éxito del Dashboard:**

- 3 páginas interactivas conectadas<br>
- 15+ visualizaciones complementarias<br>
- 20+ medidas DAX personalizadas<br>
- 6 slicers para exploración dinámica<br>
- Tiempo de carga: <2 segundos

**📸 Capturas de Pantalla<br>**

**Dashboard 1: Executive Overview<br>**

![Executive Overview](images/dashboard_1_executive.png)<br>
Vista general con KPIs principales y distribución de attrition

**Dashboard 2: Attrition Deep Dive**

![Attrition Analysis](images/dashboard_2_attrition.png)<br>
Análisis de causas raíz y roles críticos

**Dashboard 3: Employee Demographics**

![Demographics](images/dashboard_3_demographics.png)<br>
Perfil demográfico y análisis generacional

**🔗 Archivos del Proyecto**

- Dashboard interactivo: Descargar archivo .pbix<br>
- Dataset: HR_Analytics_Dataset.csv<br>
- GitHub: Repositorio completo

**👨‍💻 Sobre mí<br>**
Diego Alejandro Pérez Pastrana<br>
Analista de Datos con experiencia en Power BI, SQL y análisis de negocio.<br>
📧 Email: devcode480@gmail.com<br>
💼 LinkedIn: linkedin.com/in/diego-perez480/<br>
🐙 GitHub: github.com/AleCodeDev

**📝 Notas Técnicas<br>**
- Versión de Power BI: Desktop (última versión)<br>
- Fecha de creación: Diciembre 2024<br>
- Tiempo de desarrollo: 3 días<br>
- Nivel del proyecto: Intermedio

Este proyecto fue desarrollado como parte de mi portafolio de análisis de datos, demostrando mis habilidades en Power BI, DAX, visualización de datos y business intelligence aplicado a recursos humanos.
