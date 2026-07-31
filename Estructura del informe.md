la Estructura del informe debe estar hecha en base al casi de emergencias clinicas [[Caso Actual]]

**NOTAS**:
- Informe 15 puntos
- Interfaz 10 puntos
- defensa 5 puntos
- conocimiento del trabajo 5 puntos
- **Total 35 puntos**
# Estructura Normativa y Estándares de Documentación para Proyectos de Grado en Ingeniería de Sistemas Informáticos

## Componentes Preliminares y Protocolos Formales de Presentación

Las páginas preliminares constituyen el marco institucional y de navegación del informe formal. Cumplen la función de validar administrativamente el documento, certificar la autoría y facilitar la localización de los contenidos técnicos a los tribunales evaluadores.

### Portada y Carátula Exterior

La portada representa la presentación institucional formal del proyecto de grado. Debe contener, alineados según la normativa estandarizada de la facultad correspondiente:

- **Identificación Institucional**: Nombre oficial de la universidad, facultad y carrera profesional.
    
- **Emblema**: Logotipo institucional en alta resolución.
    
- **Título del Proyecto**: Nombre descriptivo y delimitado del trabajo, explicitando el objeto de estudio, la tecnología o enfoque computacional principal y el ámbito de aplicación
    
- **Autores y Tutores**: Nombre completo del postulante o autor, acompañado del nombre completo y grado académico del tutor o director de proyecto.
    
- **Datos de Edición**: Ciudad, país y año formal de presentación.
    
### Resumen Ejecutivo y Abstract

Representa la síntesis analítica del trabajo en una extensión máxima de 300 palabras. Debe redactarse en un único párrafo estructurado que abarque: la problemática abordada, el objetivo principal, el marco metodológico o proceso de software aplicado, los resultados tecnológicos alcanzados y las conclusiones financieras o funcionales más relevantes. Debajo del resumen se deben incluir entre 4 y 6 palabras clave (Keywords). Esta sección debe traducirse íntegramente al inglés bajo el título de _Abstract_.

### Índices Formales del Documento

El informe debe incorporar cuatro tipos de índices automatizados mediante notación decimal jerárquica:

- **Índice de Contenidos**: Estructura capitular detallando capítulos, secciones y subsecciones con su correspondiente paginación.
    
- **Índice de Figuras e Ilustraciones**: Relación cronológica y paginada de esquemas arquitectónicos, diagramas UML, mapas de procesos y capturas de interfaz de usuario.
    
- **Índice de Tablas**: Lista estructurada de cuadros comparativos, matrices de trazabilidad, diccionarios de datos y presupuestos.
    
- **Índice de Ecuaciones y Acrónimos**: Glosario codificado de notaciones matemáticas, fórmulas financieras y siglas tecnológicas (tales como API, CI/CD, REST, DBMS, WACC).
    

## Capítulo I: Marco de Referencia y Planteamiento del Proyecto

Este capítulo introduce el contexto operativo de la investigación, justifica la necesidad de la intervención informática y establece las fronteras formales que rigen la ejecución del proyecto.

### 1.1 Introducción y Antecedentes Generales

La introducción presenta una visión global de la temática, situando al lector en el ámbito de los sistemas informáticos específicos a desarrollar. En los antecedentes, se detalla la evolución del escenario operativo en la organización o dominio tecnológico estudiado, analizando críticamente soluciones previas implementadas, deficiencias operativas persistentes e investigaciones comparables a nivel local e internacional.

### 1.2 Planteamiento y Formulación del Problema

- **1.2.1 Identificación y [[Problema y Diagnostico|Diagnóstico]] del Problema**: Descripción cualitativa y cuantitativa de los síntomas, causas y efectos observados en el escenario actual. Se recomienda fundamentar el diagnóstico mediante herramientas de análisis de causas raíz (como el [[4.2. Arbol de problemas|árbol de problemas]] o el diagrama de Ishikawa), demostrando que la problemática radica en la ineficiencia de procesamiento, la falta de automatización, la vulnerabilidad de la información o la ausencia de integración entre sistemas.
    
- **[[Problema y Diagnostico|1.2.2 Formulación del Problema]]**: Declaración precisa e interrogativa del problema central. Debe relacionar directamente la variable dependiente (las deficiencias operativas u organizacionales) con la variable independiente (la solución tecnológica o sistema informático propuesto).
    
### 1.3 Formulación de Objetivos

- **1.3.1 Objetivo General**: Define la meta integral del proyecto. Debe redactarse iniciando con un verbo en infinitivo de nivel taxonómico alto (por ejemplo, _Desarrollar_, _Implementar_, _Diseñar e Construir_), precisando el objeto de estudio, la población o entidad beneficiaria, y el enfoque metodológico o tecnológico a emplear.
    
- **1.3.2 Objetivos Específicos**: Secuencia cronológica y metodológica de pasos que garantizan el cumplimiento estricto del objetivo general. En la carrera de sistemas informáticos, estos objetivos deben alinearse secuencialmente con las fases del ciclo de vida del software: diagnóstico de requerimientos, diseño arquitectónico y de persistencia, desarrollo de componentes, ejecución de pruebas de software y evaluación de viabilidad económica.
    

### 1.4 Delimitación y Alcances del Proyecto

Se establecen las fronteras operativas para evitar ambigüedades durante la evaluación del proyecto:

- **Alcance Funcional**: Detalle explícito de los módulos, procesos de negocio y funcionalidades que el sistema asumirá y, de manera equitativa, la aclaración expresa de aquellas funciones que quedarán fuera del alcance del proyecto.
    
- **Alcance Tecnológico**: Especificación de las plataformas de despliegue, entornos de ejecución (web, móvil, escritorio), lenguajes de programación y límites de compatibilidad garantizados ([[Viabilidad del sistema|Necesidades de hardware y software]]).
    
- **Delimitación Geográfica y Temporal**: Ubicación física o institucional del estudio y periodo cronológico asignado para la ejecución y recolección de datos. [[Planeacion y Control de Actividades | Cronograma de su analisis]]
    

### 1.5 Justificación de la Investigación

Sustentación de la conveniencia del proyecto a través de tres dimensiones fundamentales:

- **Justificación Técnica**: Relevancia de incorporar nuevas arquitecturas de software, tecnologías emergentes, patrones de diseño, estándares de seguridad y marcos de trabajo que modernicen la infraestructura computacional existente (Aqui entra [[Viabilidad del sistema|viabilidad tecnica]]).
    
- **Justificación Económica**: Demostración preliminar de cómo el sistema reducirá los costos de operación, optimizará tiempos de procesamiento y generará un retorno sobre la inversión en la organización objetivo.
    
- **Justificación Social u Organizacional**: Beneficios directos e indirectos para los usuarios finales, clientes o la estructura administrativa de la entidad afectada.
- **Justificacion investigativa**:
	- Enfoque
	- Metodo
	- Tipo
## Capítulo II: Marco Teórico y Conceptual

El marco teórico proporciona la fundamentación científica, conceptual y tecnológica necesaria para comprender las decisiones de diseño tomadas durante la solución del problema. Debe evitarse la mera transcripción de definiciones aisladas, priorizando una revisión sistemática, contextualizada y rigurosa.

### 2.1 Estado del Arte y Trabajos Relacionados

Análisis comparativo de proyectos de titulación, artículos científicos y soluciones comerciales afines. Se debe incluir una tabla comparativa que contraste las tecnologías empleadas, las metodologías de desarrollo, las métricas de rendimiento y las brechas funcionales que el presente proyecto pretende resolver.

### 2.2 Fundamentos de Ingeniería de Software y Arquitectura

Desarrollo conceptual de los patrones arquitectónicos seleccionados para el proyecto (tales como Arquitectura Limpia, Microservicios, Modelo-Vista-Controlador - MVC, o Arquitectura Orientada a Eventos). Se debe justificar teóricamente por qué la arquitectura elegida satisface los atributos de calidad del sistema, como la escalabilidad, la mantenibilidad y el desacoplamiento.

### 2.3 Tecnologías de Almacenamiento y Gestión de Datos

Exposición de las bases teóricas de los sistemas gestores de bases de datos relacionales (SGBD SQL) y no relacionales (NoSQL documentales, clave-valor, orientadas a grafos). Explicación teórica de los paradigmas de programación empleados (Orientado a Objetos, Funcional, Reactivo) y de los frameworks computacionales seleccionados para el desarrollo del _frontend_ y _backend_.

### 2.4 Normativas, Estándares y Marcos de Seguridad

Presentación de los estándares internacionales que regulan el ciclo de vida de desarrollo:

- **ISO/IEC/IEEE 29148**: Marco estándar para los procesos de ingeniería de requisitos en sistemas de software.
    
- **ISO/IEC 25010**: Modelo para la evaluación de las características de calidad del producto de software.
    
- **OWASP Top 10**: Guía de principios de seguridad para la mitigación de vulnerabilidades en aplicaciones web y móviles.
    

## Capítulo III: Ingeniería del Proyecto y Gestión de Requisitos

En este capítulo se expone el trabajo sustancial de la carrera: la aplicación sistemática de principios de ingeniería para transformar necesidades operativas en modelos de software analíticos rigurosos.

### 3.1 Marco Metodológico del Ciclo de Vida

Justificación e implementación de la metodología de desarrollo de software seleccionada. El autor debe fundamentar la elección entre metodologías tradicionales/pesadas (como RUP o Cascada) o marcos ágiles (como Scrum, Kanban, Extreme Programming o ASD) en función del nivel de incertidumbre, el tamaño del equipo y la frecuencia de entregas requerida. Se deben detallar formalmente los roles, artefactos y eventos o fases adaptados concretamente para el proyecto. [[Planeacion y Control de Actividades]]

### 3.2 Ingeniería de Requisitos según la Norma ISO/IEC/IEEE 29148

Alineado con los estándares internacionales de ingeniería, se deben documentar formalmente las fases de definición e ingeniería de requisitos:

- **Elicitación de Requisitos de Interesados (StRS)**: Levantamiento de las necesidades de las partes interesadas mediante técnicas estructuradas (entrevistas, encuestas, talleres de lluvia de ideas, observación directa o prototipado).
    
- **Especificación de Requisitos de Software (SRS / ERS)**: Definición precisa, no ambigua, verificable y priorizada de los requisitos del sistema.
    
    - **Requisitos Funcionales (RF)**: Declaración detallada de los servicios, operaciones computacionales, reglas de negocio y transformaciones de datos que el sistema debe ejecutar.
        
    - **Requisitos No Funcionales (RNF)**: Restricciones operativas de rendimiento, concurrencia, disponibilidad, usabilidad, mantenibilidad y seguridad física y lógica, categorizadas según la norma ISO/IEC 25010.
        
- **Matriz de Trazabilidad de Requisitos**: Cuadro estructurado que vincula cada necesidad del negocio con su correspondiente requisito funcional, módulo arquitectónico, caso de uso y caso de prueba, garantizando el control de cambios.
    
### 3.3 Modelado y Diseño del Sistema mediante UML

Representación gráfica y conceptual del sistema utilizando el Lenguaje Unificado de Modelado (UML 2.5):

- **Diagramas de Casos de Uso de Alto Nivel**: Delimitación de los actores (humanos o sistemas externos) y sus interacciones formales con las fronteras del sistema.
    
- **Especificación Expandida de Casos de Uso**: Tablas detalladas para los casos de uso críticos, definiendo actores, precondiciones, flujo principal o feliz, flujos alternativos, excepciones y postcondiciones.
    
- **Diagramas de Secuencia**: Representación del intercambio temporal de mensajes entre objetos y componentes a través de las distintas capas de la arquitectura.
    
- **Diagramas de Actividades**: Flujo de trabajo algorítmico y lógico de los procesos de negocio complejos o reglas de cálculo.
    
- **Diagrama de Clases de Dominio y de Diseño**: Representación estática de las entidades, sus atributos, métodos, y sus relaciones de asociación, agregación, composición y herencia.
    

## Capítulo IV: Construcción, Persistencia de Datos y Arquitectura de Despliegue

Este capítulo describe la transición desde el diseño conceptual hacia la implementación física del código, la persistencia de la información y la topología de la infraestructura operacional.

### 4.1 Ingeniería y Persistencia de Datos

- **Modelo Entidad-Relación (DER) y Esquema Relacional**: Mapeo completo de las entidades organizacionales, especificando claves primarias (PK), claves foráneas (FK), cardinalidades y reglas de normalización (1FN, 2FN, 3FN). En proyectos orientados a NoSQL, se deben presentar las estructuras de colecciones o documentos JSON/BSON.
    
- **Diccionario de Datos**: Matriz exhaustiva que documenta cada tabla o colección, indicando el nombre del campo, tipo de dato, longitud, restricciones (NOT NULL, UNIQUE, CHECK), descripción funcional y claves.
    
- **Optimización e Integridad**: Presentación de procedimientos almacenados, disparadores (_triggers_), vistas e índices diseñados para garantizar la integridad referencial y optimizar el rendimiento en transacciones complejas.
    

### 4.2 Arquitectura de Componentes e Interfaces

- **Diagrama de Componentes UML**: Estructura modular del software, ilustrando los paquetes, bibliotecas, controladores, servicios API y sus dependencias técnicas.
    
- **Diseño UI/UX**: Presentación de las interfaces de usuario mediante wireframes de baja fidelidad y prototipos interactivos de alta fidelidad. Se debe incluir la justificación de las decisiones de diseño basadas en usabilidad, accesibilidad y capacidad de adaptación computacional (_responsive design_).
    
- **Especificación de Servicios API e Integraciones**: Definición formal de las rutas (_endpoints_), métodos HTTP (GET, POST, PUT, DELETE), formatos de intercambio de datos (JSON/XML) y esquemas de autenticación y autorización (JWT, OAuth2).
    

### 4.3 Infraestructura y Despliegue Operativo

- **Diagrama de Despliegue UML**: Representación de la topología de hardware y entorno de ejecución, mapeando nodos físicos o virtuales (servidores web, servidores de base de datos, balanceadores de carga) y los artefactos distribuidos en cada uno.
    
- **Infraestructura de Servidores y Servicios Cloud**: Configuración del entorno de producción (AWS, Azure, GCP o servidores _On-premise_), uso de contenedores (Docker, Kubernetes) y definición de canalizaciones de integración y despliegue continuo (CI/CD).
    

## Capítulo V: Verificación, Validación y Aseguramiento de Calidad

Esta sección demuestra cuantitativa y cualitativamente que el producto de software construido funciona de forma correcta, cumple con los requisitos especificados y está libre de fallas críticas.

### 5.1 Plan y Niveles de Pruebas de Software

Descripción detallada de la estrategia de pruebas aplicada. Se deben estructurar tablas para los casos de prueba indicando: identificador, requisito asociado, precondiciones, datos de entrada, resultado esperado, resultado obtenido y estado final (Aprobado/Fallido).

|**ID Caso**|**Requisito Asociado**|**Entrada / Procedimiento**|**Resultado Esperado**|**Resultado Obtenido**|**Estado**|
|---|---|---|---|---|---|
|**UT-001**|RF-01 (Autenticación)|Envío de credenciales válidas en JSON|Retorno de Token JWT con HTTP 200|Token emitido correctamente|Aprobado|
|**ST-014**|RNF-02 (Rendimiento)|Carga simulada de 500 req/seg con JMeter|Tiempo de respuesta promedio < 1.5 s|Respuesta promedio de 0.85 s|Aprobado|

- **Pruebas Unitarias**: Automatización de pruebas de caja blanca sobre métodos y funciones críticas del negocio, indicando el porcentaje de cobertura de código (_code coverage_) mediante herramientas del entorno.
    
- **Pruebas de Integración**: Verificación de la comunicación entre la capa de persistencia, lógica de negocio y servicios externos.
    
- **Pruebas Funcionales y de Sistema**: Verificación de caja negra para validar el cumplimiento extremo a extremo (_E2E_) de los flujos de trabajo.
    
- **Pruebas No Funcionales**: Ejecución de pruebas de carga, estrés y seguridad para verificar la tasa de transferencia, latencia bajo demanda concurrente e inmunidad ante inyecciones de código.
    
- **Pruebas de Aceptación de Usuario (UAT)**: Evaluación de la experiencia de uso con usuarios finales reales, aplicando metodologías como la escala de usabilidad del sistema (SUS - _System Usability Scale_).
    

### 5.2 Evaluación de Atributos de Calidad (ISO/IEC 25010)

Análisis de los resultados de calidad evaluando las 8 características del estándar: adecuación funcional, eficiencia de desempeño, compatibilidad, usabilidad, fiabilidad, seguridad, mantenibilidad y portabilidad.

## Capítulo VI: Evaluación Económica, Financiera y Estimación del Proyecto

El capítulo económico evalúa la viabilidad financiera de la solución tecnológica. Demuestra formalmente si los costos de desarrollo e infraestructura se justifican en función de los beneficios o ahorros operativos generados para la organización.

### 6.1 Estimación de Esfuerzo de Software mediante Modelos Algorítmicos

Antes de estructurar el presupuesto, se debe estimar rigurosamente el esfuerzo de desarrollo. Para ello se aplica el **Modelo Constructivo de Costos (COCOMO II)** o el análisis de **Puntos de Función (FP)**.

En el modelo COCOMO, el esfuerzo $E$ expresado en meses-persona y el tiempo de desarrollo $T_{dev}$ en meses se calculan mediante las siguientes expresiones matemáticas:

$$E = a \times (KLOC)^b \times \prod_{i=1}^{15} EAF_i$$

$$T_{dev} = c \times (E)^d$$

Donde $KLOC$ representa la cantidad estimada de miles de líneas de código fuente, $EAF$ representa el factor de ajuste del esfuerzo derivado de los atributos del producto, hardware, personal y proyecto, mientras que $a, b, c, d$ son constantes asociadas a la complejidad del software (orgánico, semi-acoplado, empotrado).

### 6.2 Presupuesto Directo, Indirecto y Costos de Operación

Desglose detallado de las inversiones requeridas para el ciclo de vida del proyecto:

- **Costos Directos**: Honorarios calculados por costo hora/hombre de los roles participantes (Analista, Arquitecto de Software, Desarrolladores Frontend/Backend, Especialista QA, Diseñador UI/UX).
    
- **Costos Indirectos**: Depreciación proporcional de hardware, costo de servicios públicos, conexión a internet y uso de instalaciones.
    
- **Costos Operativos e Infraestructura Cloud**: Licencias de desarrollo, dominio web, certificados de seguridad, instancias de base de datos administradas y servidores cloud.
    

### 6.3 Evaluación Financiera y Métricas de Rendimiento

Construcción del Flujos de Caja Proyectado a un horizonte temporal de 3 a 5 años, contrastando la inversión inicial y los costos operativos contra los ahorros monetarios o ingresos generados por la automatización. Se aplican las siguientes métricas de rentabilidad:

|**Indicador Financiero**|**Expresión Matemática**|**Criterio de Decisión y Viabilidad**|
|---|---|---|
|**Valor Actual Neto (VAN / VPN)**|$$VAN = \sum_{t=1}^{n} \frac{CF_t}{(1 + r)^t} - I_0$$|Viable si $VAN > 0$. Expresa el valor monetario neto creado descontado a la tasa $r$.|
|**Tasa Interna de Retorno (TIR)**|$$\sum_{t=1}^{n} \frac{CF_t}{(1 + TIR)^t} - I_0 = 0$$|Viable si $TIR \ge r$. Refleja la tasa porcentual efectiva de rendimiento.|
|**Retorno de Inversión (ROI)**|$$ROI = \left( \frac{\text{Beneficio Neto Total}}{I_0} \right) \times 100$$|Mide el porcentaje de capital recuperado por cada unidad monetaria invertida.|
|**Relación Beneficio / Costo (B/C)**|$$B/C = \frac{\sum \text{VP de Beneficios}}{\sum \text{VP de Costos}}$$|Viable si $B/C > 1$. Mide el rendimiento bruto obtenido por unidad de gasto.|

Donde $CF_t$ representa el flujo de caja en el periodo $t$, $I_0$ la inversión inicial, $r$ la tasa de descuento o costo de oportunidad del capital (WACC) y $n$ los periodos evaluados.

## Capítulo VII: Conclusiones, Recomendaciones y Trabajos Futuros

Esta sección sintetiza los hallazgos del trabajo de titulación, evalúa cuantitativamente el cumplimiento de los objetivos y proyecta la evolución del producto de software.

### 7.1 Conclusiones

Las conclusiones deben guardar una correspondencia exacta con el objetivo general y los objetivos específicos planteados en el Capítulo I. Deben evitarse enunciados vagos, estructurando afirmaciones concretas basadas en los datos obtenidos en la fase de pruebas y en la evaluación financiera. Cada objetivo específico debe responderse explicitando cómo la solución tecnológica logró resolver la problemática planteada.

### 7.2 Recomendaciones

Sugerencias operativas para la continuidad del software:

- **Mantenimiento Evolutivo**: Propuestas para la incorporación de nuevos módulos, algoritmos avanzados, analítica de datos o integración con inteligencia artificial en iteraciones futuras.
    
- **Gobernanza y Sostenibilidad**: Directrices sobre políticas de copias de seguridad (_backups_), auditorías de seguridad periódicas y mantenimiento preventivo del entorno servidor.
    

## Secciones Finales y Anexos TÉCNICOS

Las secciones finales estructuran la documentación técnica extendida que respalda la ejecución del proyecto.

### Anexos

Documentos técnicos que por su longitud interrumperían la fluidez del texto capitulado, pero que resultan indispensables para la verificación del jurado:

- **Anexo A: Manual de Usuario**: Guía ilustrada paso a paso para la operación del sistema por cada rol de usuario.
    
- **Anexo B: Manual de Instalación y Despliegue**: Guía técnica detallada para la configuración del entorno servidor, ejecución de scripts de base de datos, compilación de código y despliegue en la nube.
    
- **Anexo C: Actas de Conformidad y Documentos Institucionales**: Cartas formales firmadas por las autoridades de la empresa o institución receptora, certificando la conformidad con el sistema.
    
- **Anexo D: Instrumentos de Recolección de Datos**: Formatos completos de las encuestas, guiones de entrevista e instrumentos aplicados durante el diagnóstico.
    
- **Anexo E: Código Fuente de Algoritmos Complejos**: Muestras de código representativo para procedimientos algorítmicos críticos o configuraciones de infraestructura como código.
    

## Matriz Resumen de Artefactos por Capítulo

La siguiente tabla resume la correlación entre cada capítulo del informe, sus entregables técnicos correspondientes y los estándares de ingeniería aplicables:

|**Capítulo del Informe**|**Artefactos Técnicos y Entregables Clave**|**Estándares y Marcos Aplicables**|
|---|---|---|
|**I. Marco de Referencia**|Matriz de diagnóstico, Árbol de problemas, Matriz de objetivos y alcances.|Metodología de Marco Lógico (MML).|
|**II. Marco Teórico**|Estado del arte comparativo, Diagramas de patrones de arquitectura.|ISO/IEC 25010, IEEE Curricula.|
|**III. Ingeniería del Proyecto**|Documento StRS, SRS, Matriz de Trazabilidad, Diagramas UML (Casos de uso, Clases, Secuencia, Actividades).|**ISO/IEC/IEEE 29148**, UML 2.5.|
|**IV. Construcción y Despliegue**|Modelo ER, Diccionario de Datos, Diagrama de Componentes, Wireframes UI/UX, Diagrama de Despliegue.|CMMI-DEV, Normalización Relacional.|
|**V. Calidad y Pruebas**|Matriz de Pruebas (Unitarias, Integración, Carga), Métricas de cobertura, Test SUS.|**ISO/IEC 25010**, IEEE 829.|
|**VI. Evaluación Económica**|Estimación COCOMO II, Presupuesto, Flujo de Caja, Cálculo de VAN, TIR, ROI, B/C.|COCOMO II, WACC, VAN / TIR.|
|**VII. Conclusiones y Anexos**|Cuadro de cumplimiento de objetivos, Manual de Usuario, Manual de Despliegue, Actas de conformidad.|Estándares de Documentación de Software.|
        

### **CONSEJOS CLAVE PARA EL EJERCICIO PROFESIONAL**

> **1. Rige la objetividad:** Todo informe profesional debe redactarse en voz impersonal o tercera persona (_"Se identificó que...", "Se procedió a..."_). Se evitan apreciaciones subjetivas o juicios de valor sin sustento en datos.
> 
> **2. Trazabilidad absoluta:** Existe un hilo conductor obligatorio: _El problema identificado en el diagnóstico debe reflejarse exactamente en el árbol de problemas, resolverse mediante los objetivos, y materializarse funcionalmente en la propuesta de software._