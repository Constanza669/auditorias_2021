##  Análisis del rendimiento de auditorias internas
**Por Constanza Espinoza**

 Dataset analiza rendimiento de auditorias internas realizadas a los distintos contratos durante el actual año

## Set de datos

Dataset obtenido de empresa privada Somacor S.A.

## Herramientas utilizadas

  - Python
  - Jupiter notebooks
  - Pandas
  - Numpy
  - Matplotlip
  - Seaborn
  
## Historia

En la empresa se realiza de manera anual auditorias internas con el fin de realizar seguimiento al Sistema de Gestión que se implementó. 
Se realizó auditoria de Salud ocupacional, seguridad, calidad y medio ambiente asociado a la normativa ISO 9001, ISO 14001, ISO 45001 y requisitos legales aplicables. 

La metodologia consiste en avisar al auditado con un mes de anticipación cuando se realizará la auditoria y se envía un check list con los distintos topicos o requisitos que serán evaluados. El mismo día de la auditoria, se entregan resultandos y no conformdiades parciales, esto debido a que se implementó un plazo de 6 días para que el auditado envíe las evidencias faltantes y así poder actualizar el informe final y su cumplimiento, es por ello que la revisión se divide en no conformidades parciales y finales y cumplimiento parcial y final.


 
## Conclusiones 

- ¿Existe alguna tendencia de resultados entre los distintos contratos frente a las distintas auditorias?

Se tomó una muestra para revisar el comportamiento y se obtuvo lo siguiente:

Anglo Amercian: como se observa en la tabla, el contrato mantuvo no conformidades en un rango parecido, es decir, le fue bien en todas las auditorias (por las bajas NC).
CMPC: mantiene un rango promedio, la auditoria de Higiene mantiene un valor mas alto en comparación a las otras.
El Peñon: mantiene el mismo rango de resultados en todas las auditorias.
INCO: mantiene un rango promedio con NC mas altas, sin embargo le va mejor en la auditoria de Medio Ambiente.
Quebrada Blanca: contrato tiene resultados altos, a excepción de la auditoria de Medio Ambiente.
Geologia: mantiene un rango alto de NC, donde mejor le va es en la auditoria de Medio Ambiente
**Respuesta: existe un patrón. De acuerdo a la revisión aleatoria, los contratos o les va bien en todas o en ninguna (comparando entre NC) permitiendo evaluar la gestión de los administradores de cada contrato. Otro patrón destacable es el rango de NC por auditorias, donde mas NC hubieron fue en la auditoria de Higiene y en la que mejores resultados demostraton fue en la de medio ambiente.**


- ¿Hubo un aumento significativo en el cumplimiento frente al plazo entregado?

**Respuesta Dentro del plazo se recolectaron 615 no conformidades y se mantuvieron 235 como definitivas, es decir, se trataron 372, por lo tanto, hubo una eficiencia de 62% en incorporar nueva metodologia (plazo)**

- ¿Cúal o cuales fueron los contratos que mejor resultado tuvieron?, ¿Y los peores?

**Respuesta**
**Los contratos con menos no conformidades: CMPC con 2, SGO con 9 y Cerro Colorado con 10.
Los contratos con mas no conformidades: INCO con 77, CDA con 62 y Spence con 61.
Los contratos con mas no conformidades tratadas: INCO con 46, Geologia con 41 y Casa Matriz con 39.
Los contratos con menos no conformidades tratadas: CDA con 6, Lavandería con 13
Por lo tanto, los contratos con mejores resultados son: CMPC (con NC preliminares) e INCO (con tratadas) y con peores son: INCO (con NC preliminares) y CDA (sin tratar)**

- ¿Cúal auditoria tuvo mejores resultados?, ¿y la peor?

Resultados de la auditoria calidad: 74 no conformidades durante el día de la auditoria y 30 definitivas, por lo tanto hubo una eficiencia de 41%.
Resultados de la auditoria seguridad: No se pudo obtener el valor

Resultados de la auditoria medio ambiente: 24 no conformidades durante el día de la auditoria y 4 definitivas, por lo tanto hubo una eficiencia de 83%.

Resultados de la auditoria de Higiene y salud ocupacional: 325 no conformidades durante el día de la auditoria y 120 definitivas, por lo tanto hubo una eficiencia de 63%.
Por otra parte, las NC mas tratadas fueron las de Higiene y las menos de Medio ambiente, a pesar de que esta última sea la que menos NC mantiene.

**Respuesta: la auditoria con mejores resultados fue la de medio ambiente y con peores la de Higiene y Salud Ocupacional**

- ¿Qué topicos auditados tuvieron mejores resultados?, ¿y los peores?

**Respuesta:**

Auditoria de Calidad:
Los requisitos con mejores resultados fueron "Satisfacción al cliente", "Comunicación, Participación y Consulta", "Control Documental" y "Productos y Servicios Suministrados Externamente".
Por otra parte, los peores requisitos auditados fueron: "Capacitación y Competencia", "Identificación de Riesgos y Oportunidades" y "Requisitos Legales".
Auditoria de Higiene y Salud Ocupacional:
Los requisitos con mejores resultados fueron: "Exposición a frío", "Hipobaria" y "Vibraciones".
Por otra parte, los peores requisitos auditados fueron: "Psicosocial", "Iluminación" y "Tmert".
Auditoria de Medio Ambiente:
Los requisitos con mejores resultados fueron: "Residuos Peligrosos" y "Sustancias Peligrosas"
Por otra parte, los peores requisitos auditados fueron: "Identificación Aspectos e Impactos Ambientales" y "Objetivos de Medio Ambiente" A pesar de la comparación, el rango en esta auditoria es muy parecido.
Auditora de Seguridad:
Los requisitos con mejores resultados fueron: "Riesgos de Fatalidad", "Identificacion Peligros y Evaluacion de Riesgos" y "Control Documental"
Por otra parte, los peores requisitos auditados fueron: "Objetivos de Seguridad y Salud Ocupacional", "Comite paritario de higiene y seguridad" y "Comunicacion, participacion y consulta".
