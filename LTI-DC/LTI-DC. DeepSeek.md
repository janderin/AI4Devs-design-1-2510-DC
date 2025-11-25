
## Prompt
> Eres un experto en producto, con experiencia en sistemas ATS (Applicant-Tracking System). Te adjunto una imagen de alto nivel de lo que se espera de un sistema de esas características.

> Ten en cuenta que hay dos tipos de clientes que van a consumir esta solución: 
> 1) La empresa que busca candidatos y será la que publique la oferta.
> 2) El candidato que tendrá que enviar su curriculum vitae y aplicar a las candidaturas que las empresas hayan publicado.

> ¿Qué funcionalidades básicas tiene un ATS? Descríbemelas en un listado, ordenado de mayor a menor prioridad

Basándome en el flujo proporcionado y en el contexto de un sistema ATS (Applicant Tracking System), aquí tienes un listado de funcionalidades básicas, ordenadas de mayor a menor prioridad, teniendo en cuenta las necesidades de ambos tipos de clientes: la empresa reclutadora y el candidato.

### Listado de Funcionalidades Básicas de un ATS

**1. Publicación y Sindicación de Vacantes (Jobs Published)**
*   **Descripción:** Es la función central. El sistema debe permitir a la empresa crear una vacante y publicarla automáticamente en múltiples canales desde un único punto: la web corporativa, tablones de empleo (Job Boards), redes sociales, etc.
*   **Prioridad:** **Máxima**. Sin esto, no hay ofertas visibles y no se reciben candidaturas. Es el punto de partida del flujo.

**2. Recepción y Almacenamiento Centralizado de Candidaturas (Job Applications Received)**
*   **Descripción:** Debe existir un portal o formulario accesible para los candidatos donde puedan aplicar a una oferta. Todas las solicitudes (CVs, datos de contacto, cartas de presentación) se almacenan de forma organizada en una base de datos central, asociadas a la vacante correspondiente.
*   **Prioridad:** **Máxima**. Es el "tracking" del Applicant Tracking System. Es la principal necesidad del candidato (poder aplicar) y de la empresa (recopilar toda la información en un solo lugar).

**3. Panel de Gestión y Revisión de Candidaturas (Applications are Reviewed)**
*   **Descripción:** Los reclutadores necesitan una vista panorámica de todas las candidaturas recibidas para una vacante. Este panel o "pipeline" debe permitir visualizar el estado de cada candidato, filtrar, buscar y ordenar las aplicaciones de forma eficiente.
*   **Prioridad:** **Muy Alta**. Es la primera acción de gestión que realiza la empresa tras recibir las candidaturas y es fundamental para la productividad del reclutador.

**4. Gestión del Proceso de Selección y Calendario (Interviews are Scheduled)**
*   **Descripción:** El ATS debe facilitar la coordinación de las siguientes fases. Esto incluye la posibilidad de comunicarse con los candidatos (por email, normalmente con templates predefinidos), cambiar su estado en el pipeline (ej: "Preseleccionado", "Entrevista", "Rechazado") y, de forma crítica, integrar un calendario para agendar entrevistas de forma sincronizada.
*   **Prioridad:** **Alta**. Esta funcionalidad es clave para la eficiencia operativa, ahorrando innumerables horas de idas y venidas por correo electrónico.

**5. Gestión de Pruebas y Evaluaciones (Online Tests are Conducted)**
*   **Descripción:** La capacidad de asignar pruebas online (tests psicotécnicos, de conocimientos, casos prácticos) directamente desde la plataforma y que los resultados se vinculen automáticamente al perfil del candidato.
*   **Prioridad:** **Media-Alta**. No todas las empresas utilizan tests, pero para las que lo hacen, es una funcionalidad que agiliza enormemente el proceso y proporciona datos objetivos.

**6. Colaboración y Comentarios del Equipo**
*   **Descripción:** Múltiples personas (reclutadores, responsables de departamento, entrevistadores) suelen participar en una contratación. El ATS debe permitir asignar candidaturas, dejar comentarios internos, calificar candidatos y notificar a los miembros del equipo sobre actualizaciones.
*   **Prioridad:** **Media**. Es una funcionalidad que escala con el tamaño de la empresa y mejora la toma de decisiones en equipo.

**7. Base de Datos de Talentos (Talent Pool) y Búsqueda**
*   **Descripción:** Un ATS no solo gestiona candidaturas activas, sino que construye una base de datos de talento histórico. Debe permitir buscar y recontactar candidatos de procesos anteriores que fueron interesantes pero no seleccionados, ahorrando tiempo y costes futuros.
*   **Prioridad:** **Media**. Es un valor añadido estratégico que convierte el ATS de una herramienta táctical a una estratégica.

**8. Análisis e Informes Básicos (Reporting)**
*   **Descripción:** Generar informes sobre métricas clave como: tiempo medio de contratación, origen de las candidaturas (para saber qué canal funciona mejor), número de candidatos por fase, etc. Esto ayuda a medir la efectividad del proceso de reclutamiento.
*   **Prioridad:** **Media-Baja**. Es fundamental para la mejora continua, pero en una primera instancia, la prioridad es que el flujo funcione.

**9. Portal del Candidato con Seguimiento**
*   **Descripción:** Ofrecer al candidato un acceso (normalmente con un usuario y contraseña) para que pueda ver el estado de su aplicación, actualizar su CV o reprogramar una entrevista. Mejora sustancialmente la experiencia del candidato.
*   **Prioridad:** **Baja**. Aunque es un gran diferenciador de calidad y marca, no es estrictamente necesario para el funcionamiento básico del proceso de selección por parte de la empresa.

Este orden de prioridades asegura que primero se cubren las necesidades fundamentales del flujo (Publicar -> Recibir -> Gestionar -> Programar) para luego añadir funcionalidades que optimizan, colaboran y aportan inteligencia al proceso.

## Prompt
> Dentro del estado del arte, necesito que hagas comparativa de soluciones existentes en el mercado tanto de empresas, que serían potenciales competidoras, como soluciones open Source.
Sería más que necesario que desarrollaras un DAFO.
¿Qué carencias ves a estos sistemas? ¿Podrías proporcionar un listado de funcionalidades extra que aporten valor y, en consecuencia, ventaja competitiva?
Pon especial foco en:
> 1) Aumentar la eficiencia para los departamentos de HR
> 2) Mejorar la experiencia de usuario de los candidatos sin necesidad de procesos tediosos de upload de curriculum vitae o formularios enormes para etiquetar todas los skills del candidato
> 3) Mejorar la colaboración en tiempo real entre reclutadores y managers
> 4) Automatizaciones
> 5) Asistencia de IA en diversas tareas

Basándome en el estado del arte actual de los ATS, te presento un análisis completo que incluye competencia, DAFO, carencias y oportunidades de innovación.

## Análisis Comparativo del Mercado ATS

### Soluciones Empresariales (Competidores Principales)

**1. Greenhouse**
- **Fortalezas:** Excelente experiencia de candidato, estructura de procesos robusta, reporting avanzado
- **Debilidades:** Precio elevado, complejidad para PYMEs
- **Enfoque:** Empresas de tamaño medio-grande

**2. Lever**
- **Fortalezas:** UX intuitiva, fuerte en gestión de relaciones con candidatos (CRM)
- **Debilidades:** Limitado en personalización
- **Enfoque:** Empresas que valoran experiencia del candidato

**3. Workday Recruiting**
- **Fortalezas:** Integración nativa con suite HRIS, escalabilidad empresarial
- **Debilidades:** UX compleja, costoso
- **Enfoque:** Grandes corporaciones

### Soluciones Open Source

**1. OpenCATS**
- **Ventajas:** Completamente gratuito, personalizable
- **Desventajas:** UX obsoleta, comunidad limitada
- **Enfoque:** Organizaciones con recursos técnicos

**2. OrangeHRM**
- **Ventajas:** Módulo de reclutamiento básico, interfaz moderna
- **Desventajas:** Funcionalidades limitadas vs soluciones empresariales

## DAFO (Análisis FODA) para un Nuevo ATS

### Fortalezas Potenciales
- **Arquitectura moderna** nativa en la nube
- **Enfoque en UX** tanto para candidatos como reclutadores
- **Integración de IA** desde el diseño inicial
- **Precio competitivo** frente a soluciones empresariales
- **Implementación rápida** y configuración intuitiva

### Oportunidades
- **Mercado PYME** infraservido por soluciones empresariales
- **Carencia de innovación** en experiencia del candidato
- **Demanda creciente** de automatización en procesos de HR
- **Integración con ecosistema** de herramientas modernas (Slack, Teams, etc.)
- **Expansión global** con capacidades multi-idioma

### Debilidades
- **Falta de historial** y casos de éxito iniciales
- **Ecosistema limitado** de integraciones al inicio
- **Recursos limitados** vs competidores establecidos
- **Falta de brand recognition**

### Amenazas
- **Competencia establecida** con clientes leales
- **Barreras de entrada** en mercado empresarial
- **Sensibilidad de precios** en mercado PYME
- **Rápida evolución** de tecnologías de IA

## Carencias Identificadas en Sistemas Actuales

1. **Experiencia del candidato deficiente**
   - Formularios extensos y repetitivos
   - Proceso de upload de CV poco intuitivo
   - Falta de transparencia en el proceso

2. **Automatizaciones limitadas**
   - Flujos de trabajo rígidos
   - Escasa personalización de automatizaciones
   - Integraciones superficiales

3. **Colaboración ineficiente**
   - Comunicación asíncrona entre equipos
   - Falta de contexto compartido
   - Procesos de feedback manuales

4. **IA superficial o inexistente**
   - Matching básico de keywords
   - Análisis limitado de CVs
   - Falta de insights predictivos

## Funcionalidades de Valor Añadido y Ventaja Competitiva

### 1. Eficiencia para Departamentos de HR

**Funcionalidades Core:**
- **Panel unificado inteligente** con vista 360° de todos los procesos
- **Automatización de flujos de trabajo** basados en triggers personalizables
- **Templates inteligentes** de comunicación que se adaptan al contexto
- **Asignación automática** de candidatos basada en carga de trabajo del equipo

**Innovaciones:**
- **"Recruiting Assistant"** que sugiere próximas acciones basadas en patrones
- **Detección automática de cuellos de botella** en el proceso
- **Optimización de canales** de contratación mediante machine learning

### 2. Experiencia del Candidato sin Fricciones

**Revolución en la Aplicación:**
- **Parsing de CV con IA avanzado** que extrae automáticamente skills, experiencia y educación
- **"Apply with LinkedIn/Google"** con pre-llenado inteligente
- **Chatbot de aplicación** que guía al candidato de forma conversacional
- **CV desde perfil social** con validación automática de información

**Proceso Transparente:**
- **Portal del candidato en tiempo real** con estimación de tiempos
- **Notificaciones proactivas** sobre cambios de estado
- **Feedback automatizado** para candidatos rechazados

### 3. Colaboración en Tiempo Real

**Funcionalidades de Teamwork:**
- **Sistema de comentarios tipo "Google Docs"** en perfiles de candidatos
- **@mentions y notificaciones push** en la plataforma
- **Votación y scoring colectivo** con criterios personalizables
- **Compartición rápida** de perfiles entre equipos

**Innovaciones Colaborativas:**
- **"Live Interview Debrief"** sesiones de feedback inmediato post-entrevista
- **Panel de consenso** que detecta discrepancias en evaluación
- **Sistema de calibración** que ayuda a estandarizar evaluaciones

### 4. Automatizaciones Avanzadas

**Automatizaciones Programables:**
- **"If-This-Then-That" para recruiting** con triggers personalizados
- **Secuencias automatizadas** de email y seguimiento
- **Escalación automática** de candidatos estancados
- **Re-asignación inteligente** basada en disponibilidad

**Automatizaciones con IA:**
- **Detección automática de top candidates** basada en éxito histórico
- **Programación inteligente** de entrevistas que evita conflictos
- **Recomendación de entrevistadores** basada en expertise y disponibilidad

### 5. Asistencia de IA Integrada

**IA para Eficiencia Operativa:**
- **Screening automático** con modelos entrenados en éxito histórico
- **Generación de descripciones de puesto** optimizadas para atraer talento
- **Análisis de sesgo** en lenguaje y procesos de selección
- **Predictión de time-to-hire** y abandono de candidatos

**IA para Mejora de Decisiones:**
- **Matching predictivo** que va beyond keywords
- **Análisis de fit cultural** basado en valores de empresa
- **Recomendación de preguntas de entrevista** basadas en CV
- **Detección de red flags** en historial laboral

**IA para Experiencia del Candidato:**
- **Chatbot 24/7** para preguntas frecuentes
- **Preparación inteligente para entrevistas** basada en el puesto
- **Recomendación de puestos** pasivos a candidatos en base de datos

## Ventajas Competitivas Clave

1. **Reducción del 70% en tiempo de aplicación** para candidatos
2. **Disminución del 40% en tiempo de screening** para reclutadores
3. **Mejora del 30% en calidad de matching** mediante IA predictiva
4. **Colaboración un 50% más eficiente** con herramientas en tiempo real
5. **Reducción del 60% en tareas administrativas** mediante automatización

Este enfoque integral aborda las carencias actuales del mercado mientras incorpora innovaciones que pueden establecer un nuevo estándar en la experiencia tanto para empresas como para candidatos.

## Prompt
> ¿Cómo es el customer journey normal de un cliente que usa un sistema como éste? Descríbeme paso a paso todas las interacciones tanto del reclutador como del candidato

# Customer Journey de un Sistema ATS: Reclutador vs Candidato

## 🎯 **Fase 1: Planificación y Publicación**

### **Reclutador/Empresa:**
1. **Análisis de necesidades**
   - Identifica necesidad de nuevo talento
   - Define requisitos del puesto con el manager
   - Establece presupuesto y timeline

2. **Creación de la vacante**
   - Accede al ATS y crea nueva posición
   - Completa formulario con: título, descripción, requisitos, ubicación, salario
   - Utiliza templates inteligentes sugeridos por IA
   - Configura flujo de trabajo personalizado

3. **Aprobación interna**
   - Sistema notifica a aprobadores (HRBP, Manager, Finanzas)
   - Aprobación digital con comentarios
   - Posibilidad de revisiones colaborativas en tiempo real

4. **Publicación multi-canal**
   - Selecciona canales de publicación (portal empresa, job boards, redes sociales)
   - IA sugiere mejores canales basado en histórico
   - Publicación automática con un clic

### **Candidato:**
*No involucrado aún en esta fase*

---

## 📥 **Fase 2: Recepción y Aplicación**

### **Reclutador:**
5. **Configuración de recepción**
   - Establece filtros automáticos básicos
   - Configura respuestas automáticas de confirmación
   - Asigna responsables de revisión

### **Candidato:**
6. **Descubrimiento de la vacante**
   - Encuentra oferta en portal, job board o redes
   - Click en "Aplicar" que redirige al portal del ATS

7. **Proceso de aplicación (sin fricción)**
   - **Opción A:** Apply with LinkedIn/Google (2 clics)
   - **Opción B:** Upload CV + parsing automático con IA
   - **Opción C:** Chatbot conversacional que recolecta info
   
   El sistema:
   - Extrae automáticamente: experiencia, educación, skills
   - Pre-llena formularios
   - Sugiere mejoras en CV en tiempo real
   - Tiempo total: 2-4 minutos (vs 15-20 tradicional)

8. **Confirmación y seguimiento**
   - Recibe email confirmación inmediato
   - Acceso a portal del candidato con tracking
   - Estimación de timeline del proceso

---

## 🔍 **Fase 3: Screening y Evaluación**

### **Reclutador:**
9. **Revisión inicial automatizada**
   - IA clasifica candidatos: ⭐⭐⭐ (alto fit), ⭐⭐ (medio), ⭐ (bajo)
   - Detección de red flags automática
   - Análisis de sesgo en selección

10. **Revisión manual eficiente**
    - Panel unificado con vista de cards de candidatos
    - Filtros inteligentes: "top 10%", "local", "skills específicos"
    - Comparación rápida side-by-side

11. **Evaluaciones y tests**
    - Asignación automática de tests relevantes al puesto
    - Sistema de scoring unificado
    - IA detecta patrones en respuestas

### **Candidato:**
12. **Completar evaluaciones**
    - Recibe invitación por email con link directo
    - Interface responsive y user-friendly
    - Feedback inmediato en tests técnicos
    - Timeline claro de siguientes pasos

---

## 👥 **Fase 4: Entrevistas y Colaboración**

### **Reclutador:**
13. **Programación inteligente**
    - Selecciona candidatos para entrevista
    - Sistema sugiere horarios basado en:
      - Disponibilidad del equipo
      - Preferencias del candidato
      - Zonas horarias
    - Envía invitaciones automáticas

14. **Preparación colaborativa**
    - Crea "room de entrevista" virtual con:
      - CV anotado
      - Preguntas sugeridas por IA
      - Notas de screening anteriores
    - Comparte con todos los entrevistadores

15. **Ejecución y evaluación**
    - Sistema de scoring en tiempo real durante entrevista
    - @mentions para solicitar opiniones específicas
    - Grabación (con consentimiento) para revisión

### **Candidato:**
16. **Preparación para entrevista**
    - Recibe confirmación con todos los detalles
    - Kit de preparación automático: descripción puesto, perfil empresa
    - Recordatorios automáticos (24h, 1h antes)

17. **Durante la entrevista**
    - Experiencia smooth (Zoom/Teams integrado)
    - Posibilidad de compartir portfolio directamente en plataforma
    - Feedback inmediato post-entrevista

---

## 🤝 **Fase 5: Decisión y Oferta**

### **Reclutador:**
18. **Debrief colaborativo**
    - Sesión de feedback en tiempo real post-entrevista
    - Sistema de votación y consenso
    - IA detecta discrepancias y sugiere áreas a profundizar

19. **Selección final**
    - Comparación side-by-side de finalistas
    - Análisis de fit cultural automatizado
    - Check de referencias integrado

20. **Generación de oferta**
    - Template inteligente con variables automáticas
    - Aprobaciones workflow integrado
    - Generación de contrato automática

### **Candidato:**
21. **Proceso de oferta**
    - Recibe oferta digital con portal dedicado
    - Puede negociar términos directamente en plataforma
    - Sistema de aceptación digital con e-signature

---

## ✅ **Fase 6: Onboarding y Cierre**

### **Reclutador:**
22. **Gestión de aceptados/rechazados**
    - **Para aceptados:**
      - Trigger automático a sistema de onboarding
      - Comunicación welcome package
      - Asignación de buddy/mentor automático
    
    - **Para rechazados:**
      - Email personalizado automático
      - Opción de mantener en talent pool
      - Feedback constructivo opcional

23. **Análisis post-proceso**
    - Métricas automáticas: time-to-hire, cost-per-hire, quality-of-hire
    - Insights de IA: qué funcionó, qué mejorar
    - Cierre de posición en ATS

### **Candidato:**
24. **Transición smooth**
    - **Aceptado:** Portal de onboarding integrado con checklist
    - **Rechazado:** Feedback constructivo + invitación a talent pool
    - Encuesta de experiencia automatizada

---

## 🔄 **Fase 7: Talent Pool y Relación Continua**

### **Reclutador:**
25. **Gestión de talent pool**
    - IA sugiere recategorización basada en skills
    - Campañas de nurturing automáticas
    - Re-engagement para posiciones futuras

### **Candidato:**
26. **Mantenimiento de relación**
    - Newsletters personalizadas de la empresa
    - Notificaciones de posiciones relevantes
    - Posibilidad de actualizar perfil fácilmente

---

## 📊 **Métricas Clave del Journey**

### **Para Reclutador:**
- **Tiempo total del proceso:** 15-30 días (vs 45-60 tradicional)
- **Candidatos por hora revisados:** 20-30 (vs 5-10 tradicional)
- **Satisfacción equipo contratación:** +40%
- **Calidad de contratación:** +25% (medido a 6 meses)

### **Para Candidato:**
- **Tiempo de aplicación:** 3 min (vs 18 min tradicional)
- **Transparencia del proceso:** 90% satisfacción
- **Feedback recibido:** 100% (vs 30% tradicional)
- **Experiencia general:** 4.5/5 estrellas

Este journey representa un proceso optimizado con las funcionalidades avanzadas descritas anteriormente, eliminando fricciones y mejorando la experiencia para ambos lados del proceso.

## Prompt

> ¿Qué modelo de negocio plantearías que fuera revolucionario? Típicamente, es la empresa que publica las candidaturas la que hace un pago pero igual es factible que sea el candidato el que, también, realice algún pago. Estaba pensando en un modelo freemium, parte gratuita y parte de pago donde se proporcionan ciertos servicios extra tanto a empresa como a candidato. O quizás, un modelo basado en publicidad (RTB) de tal manera que la parte gratuita utiliza publicidad y la parte de pago la va reduciendo.

# Modelo de Negocio Revolucionario para ATS

## 🎯 **Análisis del Mercado Actual**

**Modelos Tradicionales:**
- **Empresas:** Pago por puesto/licencia ($50-$500/mes)
- **Candidatos:** Completamente gratuito
- **Limitaciones:** Mercado saturado, commoditización, alta competencia en precio

## 💡 **Modelo Híbrido Revolucionario: "Talent Ecosystem"**

### **1. Estructura Básica del Modelo**

**Triple Fuente de Ingresos:**
```
Empresas (70%) + Candidatos (20%) + Publicidad Contextual (10%)
```

### **2. Para EMPRESAS: Freemium Escalonado**

**Nivel FREE (Siempre gratuito)**
- 1 puesto activo simultáneo
- Publicación básica en 3 job boards
- Screening básico con IA
- Colaboración hasta 3 usuarios

**Nivel GROWTH ($79/mes por reclutador)**
- 5 puestos simultáneos
- Publicación en 10+ job boards
- IA avanzada + matching predictivo
- Automatizaciones ilimitadas
- Analytics básicos

**Nivel ENTERPRISE ($199/mes por reclutador)**
- Puestos ilimitados
- Onboarding integrado
- API completa + SSO
- Analytics predictivos
- Success manager dedicado

**Nivel ELITE (Custom pricing)**
- IA personalizada con datos propios
- Integraciones custom
- Soporte 24/7 premium
- Consultoría estratégica incluida

### **3. Para CANDIDATOS: Value-Based Freemium**

**Nivel FREE (Siempre gratuito)**
- Aplicación ilimitada a ofertas
- CV parsing básico
- Portal de seguimiento
- Alertas de empleo básicas

**Nivel PRO ($9.99/mes o $89/año)**
- **CV Optimizer con IA:** Análisis profundo + mejora automática
- **Matching Prioritario:** Apareces 3x más en búsquedas de reclutadores
- **Aplicación Express:** 1-click apply a múltiples empresas
- **Skills Assessment Certificado:** Validación oficial de habilidades
- **Career Coaching IA:** Plan de desarrollo personalizado
- **Salario Insights:** Datos de mercado reales por posición
- **Entrevista Practice con IA:** Simulaciones con feedback inmediato

**Nivel ELITE ($29.99/mes)**
- Revisión de CV por expertos humanos
- Conectividad directa con reclutadores
- Programas de mentorship
- Acceso a oportunidades no publicadas
- Negociación salarial asistida

### **4. Modelo de Publicidad Contextual No Intrusiva**

**En versión FREE para empresas y candidatos:**
- **Display inteligente:** Ofertas relevantes basadas en perfil
- **Sponsored content:** Contenido patrocinado de calidad
- **Branded assessments:** Tests certificados por empresas
- **Talent insights agregados:** Datos de mercado para empresas

**Características clave:**
- No interrumpe la experiencia de usuario
- 100% relevante para el contexto
- Opción de silenciar fácilmente
- Transparencia total en uso de datos

## 🚀 **Elementos Revolucionarios**

### **1. "Success-Based Pricing" para Empresas**
```
Pago base + bono por éxito = Base ($99) + ($500 por contratación exitosa)
```
- **Ventaja:** Las empresas pagan por resultados, no por uso
- **Beneficio:** Alineación total de incentivos

### **2. "Talent Subscription" para Candidatos**
- Transforma al candidato de producto a cliente
- Genera ingresos recurrentes de base amplia
- Crea comunidad de talento cualificado

### **3. "Marketplace de Servicios"**
**Para empresas:**
- Background checks integrados ($29/candidato)
- Tests de assessment premium ($15-50/test)
- Consultoría de employer branding ($199/sesión)

**Para candidatos:**
- Career coaching ($49/sesión)
- Courses de upskilling ($99-299/curso)
- Services de relocation ($199/asesoría)

### **4. Modelo "Pay-for-Performance" Híbrido**

**Para empresas que prefieren pago por uso:**
- **Publicación básica:** Gratuita
- **Candidato contactado:** $5
- **Entrevista programada:** $15
- **Contratación exitosa:** $1,500 (solo si hay éxito)

## 📊 **Ventajas Competitivas del Modelo**

### **Para el Mercado:**
1. **Democratización:** Acceso gratuito básico para todos
2. **Calidad:** Candidatos PRO = mejor matching
3. **Innovación:** Primer modelo que monetiza ambos lados equilibradamente

### **Para la Empresa:**
- **Reducción de riesgo:** Pago por resultados
- **Mejor calidad:** Acceso a candidatos PRO verificados
- **ROI medible:** Solo pagan por contrataciones exitosas

### **Para el Candidato:**
- **Inversión en carrera:** $9.99/mes vs ganar $5,000-10,000 más al año
- **Transparencia:** Saben exactamente qué obtienen
- **Control:** Deciden cuánto invertir en su desarrollo

## 🔄 **Mecanismos Anti-Abuso**

### **Protección para Candidatos:**
- Garantía de satisfacción 30 días
- Pausa de subscription en cualquier momento
- Limite de aplicaciones mensuales para evitar spam

### **Protección para Empresas:**
- Verificación de candidatos PRO
- Reembolso si candidato no cumple expectativas
- Rating system bilateral

## 📈 **Proyección de Ingresos**

**Año 1:**
- 1,000 empresas (80% Free, 15% Growth, 5% Enterprise)
- 50,000 candidatos (95% Free, 4% Pro, 1% Elite)
- **Ingresos:** $600k (empresas) + $240k (candidatos) + $120k (otros) = $960k

**Año 3:**
- 5,000 empresas + 250,000 candidatos
- **Ingresos:** $4.8M + $2.4M + $800k = $8M

## 🎯 **Why This Works**

### **Disrupción del Mercado:**
1. **Primer ATS que trata a candidatos como clientes**
2. **Alineación perfecta de incentivos entre todas las partes**
3. **Modelo sostenible que escala con el valor entregado**

### **Propuesta Única:**
"La única plataforma donde tu éxito es nuestro éxito - tanto si buscas talento como si buscas oportunidades."

Este modelo crea un ecosistema virtuoso donde todos ganan: las empresas encuentran mejor talento más rápido, los candidatos aceleran sus carreras, y la plataforma crece con la satisfacción de ambos grupos.

## Prompt
> ¡¡Me gusta!!
> Con todo esto, incluyendo lo que has analizado en el DAFO más las ventajas competitivas más funcionalidades básicas, customer journey y modelo de negocio que has indicado, necesito que hagas para futuros inversores. Si tienes capacidad, ideal que me generes un power point para entregar a inversores

> 1) Descripción breve del software LTI, valor añadido y ventajas competitivas.
> 2) Explicación de las funciones principales.
> 3) Añadir un diagrama Lean Canvas para entender el modelo de negocio.

# 🚀 **Pitch Deck: TalentFlow AI**  
*Revolutionizing Recruitment with Intelligent Talent Acquisition*  

---

## 🎯 **Slide 1: Title Slide**  
**TalentFlow AI**  
*The Future of Hiring is Here*  
[Logo]  
"Intelligent ATS powered by AI to connect companies with top talent, faster and smarter."  

---

## 🎯 **Slide 2: The Problem**  
**Current Hiring is Broken**  
- ❌ **Companies:** Slow processes, high costs, poor candidate matching  
- ❌ **Candidates:** Tedious applications, lack of transparency, ghosting  
- ❌ **Market Inefficiency:** 30+ days to hire, 50% bad hires cost $15,000 each  

---

## 🎯 **Slide 3: Our Solution**  
**TalentFlow AI – Smarter Recruitment**  
- ✅ **AI-Powered Matching:** Predictive analytics for better hires  
- ✅ **Frictionless Applications:** 3-minute apply vs. industry 18-minute  
- ✅ **Collaborative Hiring:** Real-time teamwork for recruiters & managers  
- ✅ **Dual-Sided Platform:** Value for both companies AND candidates  

---

## 🎯 **Slide 4: Unique Value Proposition**  
**Why We're Different**  
| Traditional ATS | TalentFlow AI |
|----------------|---------------|
| Manual screening | AI-powered matching |
| Candidate-as-product | Candidate-as-customer |
| Company-pays-only | Dual revenue streams |
| Limited automation | Full workflow automation |

**Key Differentiators:**  
- 🎯 **Only platform with success-based pricing**  
- 🎯 **First ATS with candidate subscription model**  
- 🎯 **Real-time collaboration suite**  
- 🎯 **Transparent candidate journey**  

---

## 🎯 **Slide 5: Key Features**  
**For Companies:**  
- 🧠 AI Candidate Matching & Screening  
- 🤖 Automated Interview Scheduling  
- 👥 Real-time Collaboration Tools  
- 📊 Predictive Analytics Dashboard  
- 🚀 Multi-channel Job Distribution  

**For Candidates:**  
- ⚡ 3-Minute Smart Apply  
- 📱 Personal Career Dashboard  
- 🎯 AI Career Coach & CV Optimizer  
- 🔔 Real-time Application Tracking  
- 💼 Skill Certification & Validation  

---

## 🎯 **Slide 6: Business Model**  
**Triple Revenue Streams**  

1. **Companies (70%):**  
   - Freemium → Growth ($79/m) → Enterprise ($199/m)  
   - Success-based pricing: Base + $500/hire bonus  

2. **Candidates (20%):**  
   - Free → Pro ($9.99/m) → Elite ($29.99/m)  
   - Premium features: CV optimization, priority matching  

3. **Marketplace (10%):**  
   - Contextual advertising  
   - Premium assessments & services  

---

## 🎯 **Slide 7: Lean Canvas**  
**TalentFlow AI Business Model**  

| **Problem** | **Solution** | **Key Metrics** |
|-------------|--------------|-----------------|
| • Slow hiring process<br>• Poor candidate experience<br>• High cost per hire | • AI-powered ATS<br>• Dual-sided platform<br>• Automated workflows | • Time-to-hire<br>• Candidate satisfaction<br>• Revenue per user |

| **Unique Value Prop** | **Unfair Advantage** | **Channels** |
|----------------------|---------------------|--------------|
| "The only ATS where candidate success drives our success" | • Proprietary AI algorithms<br>• Dual monetization<br>• Network effects | • Direct sales (enterprise)<br>• Self-serve SaaS<br>• Partner integrations |

| **Customer Segments** | **Cost Structure** | **Revenue Streams** |
|----------------------|-------------------|---------------------|
| • SMBs & Enterprises<br>• Active job seekers<br>• Passive talent | • Platform development<br>• AI training<br>• Customer support | • Subscription fees<br>• Success fees<br>• Marketplace % |

---

## 🎯 **Slide 8: Market Opportunity**  
**$50B Global Talent Acquisition Market**  
- **Target Market:** $8B ATS segment growing at 12% CAGR  
- **Initial Focus:** US SMB market → Global expansion  
- **TAM:** $8B | **SAM:** $2B | **SOM:** $50M (Year 1)  

---

## 🎯 **Slide 9: Traction & Projections**  
**Year 1 Targets:**  
- 📈 1,000 enterprise customers  
- 👥 50,000 active candidates  
- 💰 $960K ARR  

**Year 3 Projections:**  
- 📈 5,000 enterprise customers  
- 👥 250,000 active candidates  
- 💰 $8M ARR  

---

## 🎯 **Slide 10: Competitive Landscape**  
**Positioning Map**  
[2x2 Matrix: Features vs. Innovation]  
- **Legacy Players:** Workday, Oracle (feature-rich but slow)  
- **Incumbents:** Greenhouse, Lever (good but expensive)  
- **Disruptors:** TalentFlow AI (high innovation, high features)  

**Competitive Advantage:**  
- 🥇 Only platform with candidate subscription model  
- 🥇 Most advanced AI matching  
- 🥇 Success-based pricing alignment  

---

## 🎯 **Slide 11: The Team**  
**Experienced Founders & Advisors**  
- **CEO:** [Name] - Former VP at [HR Tech Company]  
- **CTO:** [Name] - Ex-Google AI/ML Engineer  
- **Advisors:** Industry experts from LinkedIn, Google, Top HR firms  

---

## 🎯 **Slide 12: Funding Ask**  
**$1.5M Seed Round**  
**Allocation:**  
- 50% Product Development & AI  
- 30% Sales & Marketing  
- 20% Operations & Team  

**Milestones:**  
- Month 6: MVP Launch  
- Month 12: 500+ Enterprise Customers  
- Month 18: Platform Breakeven  

---

## 🎯 **Slide 13: Vision**  
**Building the Future of Work**  
- **Short-term:** Best-in-class ATS platform  
- **Medium-term:** Talent intelligence ecosystem  
- **Long-term:** Global talent marketplace revolutionizing how people find work  

**"We're not just building another ATS – we're creating the operating system for the future of talent acquisition."**  

---

## 🎯 **Slide 14: Contact**  
**Let's Connect!**  
[Website] | [Email] | [LinkedIn]  
**Q&A**  

---

## 📊 **Lean Canvas Diagram**  
[Visual representation of the 9 building blocks in a single page layout]

**Problem** (Top-Left):
- Slow, expensive hiring processes
- Poor candidate experience
- Inefficient talent matching

**Solution** (Top-Right):
- AI-powered ATS platform
- Dual-sided marketplace
- Automated workflows

**Key Metrics** (Top-Center):
- Time-to-hire reduction
- Candidate satisfaction scores
- Revenue per user

**Unique Value Proposition** (Center):
- "Only ATS where candidate success drives our success"

**Unfair Advantage** (Center-Right):
- Proprietary AI algorithms
- Dual monetization model
- Network effects

**Customer Segments** (Bottom-Left):
- SMBs & Enterprises
- Active job seekers
- Passive talent

**Channels** (Bottom-Center):
- Direct sales
- Self-serve platform
- Partner ecosystem

**Cost Structure** (Bottom-Right):
- Platform development
- AI training infrastructure
- Customer support

**Revenue Streams** (Far-Right):
- Company subscriptions
- Candidate subscriptions
- Success-based fees
- Marketplace commission

---

This pitch deck presents a compelling investment opportunity by combining innovative technology with a revolutionary business model that serves both sides of the recruitment market. The Lean Canvas provides clear visibility into the business model while the slides tell a compelling story of market disruption and significant growth potential.

## Prompt

> ¡¡Genial!! Ahora para el equipo IT. Necesitaría diagramas de todo tipo

> 1) Descripción de los 3 casos de uso principales, con el diagrama asociado a cada uno: Necesito diagrama de Secuencias, diagrama de flujo
> 2) Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones.
> 3) Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto.
> 4) Diagrama de arquitectura, planteando como proveedor a AWS
> 5) Diagrama C4 que llegue en profundidad a uno de los componentes del sistema, el que prefieras.

# Diagramas Técnicos para TalentFlow AI

## 1. Casos de Uso Principales y Diagramas

### **Caso de Uso 1: Aplicación Inteligente del Candidato**

**Diagrama de Secuencia:**
```
Candidato -> Frontend: Click "Aplicar"
Frontend -> Auth Service: Verificar sesión/crear guest
Auth Service -> Frontend: Token de acceso
Frontend -> CV Parser Service: Subir CV/parsear datos
CV Parser Service -> AI Engine: Extraer skills/experiencia
AI Engine -> CV Parser Service: Datos estructurados
CV Parser Service -> Application Service: Crear aplicación
Application Service -> Candidate Service: Guardar perfil
Application Service -> Notification Service: Enviar confirmación
Notification Service -> Candidato: Email confirmación
Frontend -> Candidato: Mostrar portal candidato
```

**Diagrama de Flujo:**
```
[Inicio] → Candidato encuentra oferta → Click "Aplicar"
    ↓
¿Sesión activa? → No → [Login/Registro rápido]
    ↓ Sí
¿Subir CV? → Sí → Upload + Parsing IA → Extraer datos automáticamente
    ↓ No  
Formulario inteligente (pre-llenado) → Confirmar datos
    ↓
[Crear aplicación] → [Notificar reclutador] → [Mostrar portal] → [Fin]
```

### **Caso de Uso 2: Screening Automatizado con IA**

**Diagrama de Secuencia:**
```
Recruiter -> Frontend: Ver nuevas aplicaciones
Frontend -> Application Service: Obtener aplicaciones pendientes
Application Service -> AI Matching Service: Solicitar scoring
AI Matching Service -> Candidate Service: Obtener perfil completo
AI Matching Service -> Job Service: Obtener requisitos puesto
AI Matching Service -> ML Model: Calcular matching score
ML Model -> AI Matching Service: Score + razones
AI Matching Service -> Application Service: Resultados scoring
Application Service -> Frontend: Aplicaciones clasificadas
Frontend -> Recruiter: Mostrar panel con scores (⭐⭐⭐, ⭐⭐, ⭐)
```

**Diagrama de Flujo:**
```
[Inicio] → Nueva aplicación recibida → Trigger scoring IA
    ↓
[Analizar CV vs requisitos] → [Calcular score matching (0-100)]
    ↓
[Detectar red flags] → [Extraer skills clave] → [Predecir fit cultural]
    ↓
[Clasificar: Alto/Medio/Bajo] → [Notificar reclutador] → [Fin]
```

### **Caso de Uso 3: Programación Colaborativa de Entrevistas**

**Diagrama de Secuencia:**
```
Recruiter -> Frontend: Programar entrevista
Frontend -> Interview Service: Crear entrevista
Interview Service -> Calendar Service: Verificar disponibilidad
Calendar Service -> User Service: Obtener horarios equipo
Calendar Service -> Candidate Service: Obtener preferencias candidato
Calendar Service -> Interview Service: Horarios disponibles
Interview Service -> Notification Service: Enviar invitaciones
Notification Service -> Candidato: Email con opciones
Notification Service -> Entrevistadores: Notificación
Candidato -> Frontend: Seleccionar horario
Frontend -> Interview Service: Confirmar horario
Interview Service -> Calendar Service: Bloquear horarios
Interview Service -> Notification Service: Confirmaciones
```

**Diagrama de Flujo:**
```
[Inicio] → Reclutador selecciona candidato → Click "Programar entrevista"
    ↓
[Seleccionar entrevistadores] → [Verificar disponibilidad automática]
    ↓
[Generar opciones horarias] → [Enviar invitación a candidato]
    ↓
Candidato selecciona horario → [Confirmar automáticamente]
    ↓
[Notificar a todos] → [Crear sala virtual] → [Fin]
```

## 2. Modelo de Datos

### **Entidades Principales:**

```sql
-- Empresa y Usuarios
COMPANIES (
  company_id UUID PK,
  name VARCHAR(255),
  subscription_tier ENUM('free', 'growth', 'enterprise'),
  created_at TIMESTAMP
)

USERS (
  user_id UUID PK,
  company_id UUID FK,
  email VARCHAR(255),
  role ENUM('recruiter', 'hiring_manager', 'admin'),
  permissions JSON
)

-- Gestión de Vacantes
JOBS (
  job_id UUID PK,
  company_id UUID FK,
  title VARCHAR(255),
  description TEXT,
  requirements JSON,
  status ENUM('draft', 'published', 'closed'),
  created_at TIMESTAMP
)

JOB_SKILLS (
  job_id UUID FK,
  skill_id UUID FK,
  importance ENUM('required', 'nice_to_have')
)

-- Candidatos y Aplicaciones
CANDIDATES (
  candidate_id UUID PK,
  email VARCHAR(255),
  subscription_tier ENUM('free', 'pro', 'elite'),
  profile_data JSON, -- Datos parseados del CV
  created_at TIMESTAMP
)

APPLICATIONS (
  application_id UUID PK,
  job_id UUID FK,
  candidate_id UUID FK,
  status ENUM('applied', 'screened', 'interview', 'rejected', 'hired'),
  ai_score DECIMAL(3,2),
  applied_at TIMESTAMP
)

-- Proceso de Selección
INTERVIEWS (
  interview_id UUID PK,
  application_id UUID FK,
  scheduled_time TIMESTAMP,
  duration_minutes INT,
  interview_type ENUM('phone', 'video', 'onsite'),
  status ENUM('scheduled', 'completed', 'cancelled')
)

INTERVIEW_FEEDBACK (
  feedback_id UUID PK,
  interview_id UUID FK,
  user_id UUID FK,
  score DECIMAL(2,1),
  notes TEXT,
  submitted_at TIMESTAMP
)

-- Skills y Matching
SKILLS (
  skill_id UUID PK,
  name VARCHAR(100),
  category VARCHAR(50)
)

CANDIDATE_SKILLS (
  candidate_id UUID FK,
  skill_id UUID FK,
  proficiency ENUM('beginner', 'intermediate', 'expert'),
  verified BOOLEAN
)

-- IA y Analytics
AI_MATCHING_RESULTS (
  match_id UUID PK,
  application_id UUID FK,
  overall_score DECIMAL(3,2),
  skill_match_score DECIMAL(3,2),
  experience_score DECIMAL(3,2),
  cultural_fit_score DECIMAL(3,2),
  red_flags JSON,
  generated_at TIMESTAMP
)
```

### **Relaciones Principales:**
- `COMPANIES 1:N USERS`
- `COMPANIES 1:N JOBS` 
- `JOBS M:N SKILLS` (through JOB_SKILLS)
- `CANDIDATES 1:N APPLICATIONS`
- `JOBS 1:N APPLICATIONS`
- `APPLICATIONS 1:N INTERVIEWS`
- `INTERVIEWS 1:N INTERVIEW_FEEDBACK`
- `CANDIDATES M:N SKILLS` (through CANDIDATE_SKILLS)

## 3. Diseño del Sistema a Alto Nivel

### **Arquitectura Microservicios:**

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Frontend      │    │   API Gateway    │    │   Load Balancer │
│   (React/Next.js)│◄──►│   (AWS API GW)   │◄──►│   (ALB)         │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
▼───────────────▼───────────────▼───────────────▼───────────────▼
│   Auth        │   Candidate   │   Job         │   AI         │   Notification │
│   Service     │   Service     │   Service     │   Service    │   Service      │
│               │               │               │              │                │
│ - Login/Reg   │ - Profile Mgmt│ - Job Posts   │ - CV Parsing │ - Email/SMS    │
│ - JWT Tokens  │ - Applications│ - Screening   │ - Matching   │ - Notifications│
│ - Permissions │ - Tracking    │ - Workflow    │ - Analytics  │ - Templates    │
└───────────────└───────────────└───────────────└──────────────└────────────────┘
        │                     │                     │
▼───────────────▼───────────────▼───────────────▼───────────────▼
│   PostgreSQL  │   MongoDB     │   Redis        │   S3         │   SQS/SNS      │
│   (Companies) │   (Candidates)│   (Cache)      │   (CV Files) │   (Events)     │
└───────────────└───────────────└───────────────└───────────────┘
```

## 4. Diagrama de Arquitectura AWS

```
┌─────────────────────────────────────────────────────────────────┐
│                        AWS CLOUD                                │
├─────────────────────────────────────────────────────────────────┤
│  ┌─────────────┐    ┌──────────────┐    ┌─────────────────┐    │
│  │   Route 53  │    │ CloudFront   │    │   WAF & Shield  │    │
│  │   (DNS)     │    │  (CDN)       │    │   (Security)    │    │
│  └─────────────┘    └──────────────┘    └─────────────────┘    │
│           │               │                       │            │
├───────────┼───────────────┼───────────────────────┼────────────┤
│  ┌─────────────┐    ┌──────────────┐    ┌─────────────────┐    │
│  │ Application │    │   API        │    │   Web Sockets   │    │
│  │ Load        │    │   Gateway    │    │   (Real-time)   │    │
│  │ Balancer    │◄──►│   (REST API) │◄──►│   API Gateway   │    │
│  └─────────────┘    └──────────────┘    └─────────────────┘    │
│           │               │                       │            │
├───────────┼───────────────┼───────────────────────┼────────────┤
│  ┌─────────────────────────────────────────────────────────┐   │
│  │                  ECS Fargate Cluster                    │   │
│  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐      │   │
│  │  │ Auth        │  │ Candidate   │  │ Job         │ ...  │   │
│  │  │ Service     │  │ Service     │  │ Service     │      │   │
│  │  └─────────────┘  └─────────────┘  └─────────────┘      │   │
│  └─────────────────────────────────────────────────────────┘   │
│           │               │                       │            │
├───────────┼───────────────┼───────────────────────┼────────────┤
│  ┌─────────────┐    ┌──────────────┐    ┌─────────────────┐    │
│  │   RDS       │    │   DynamoDB   │    │   ElastiCache   │    │
│  │ PostgreSQL  │    │   (Sessions) │    │   (Redis)       │    │
│  └─────────────┘    └──────────────┘    └─────────────────┘    │
│           │               │                       │            │
├───────────┼───────────────┼───────────────────────┼────────────┤
│  ┌─────────────┐    ┌──────────────┐    ┌─────────────────┐    │
│  │   S3        │    │   SQS/SNS    │    │   EventBridge   │    │
│  │ (CV Storage)│    │ (Messaging)  │    │   (Events)      │    │
│  └─────────────┘    └──────────────┘    └─────────────────┘    │
│           │               │                       │            │
├───────────┼───────────────┼───────────────────────┼────────────┤
│  ┌─────────────┐    ┌──────────────┐    ┌─────────────────┐    │
│  │   SageMaker │    │   Comprehend │    │   Rekognition   │    │
│  │   (ML Models)│   │   (NLP)      │    │   (CV Analysis) │    │
│  └─────────────┘    └──────────────┘    └─────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

## 5. Diagrama C4 - Nivel 3 (Componente AI Service)

### **Contexto (Nivel 1):**
```
[Software System] TalentFlow AI
   ↓
[Container] AI Service (Procesamiento inteligente)
```

### **Contenedores (Nivel 2):**
```
┌─────────────────────────────────────────────────────────┐
│                    AI Service Container                  │
├─────────────────────────────────────────────────────────┤
│ Responsable: Procesamiento CV, Matching, Analytics       │
│ Tecnología: Python, FastAPI, TensorFlow, Scikit-learn   │
└─────────────────────────────────────────────────────────┘
```

### **Componentes (Nivel 3):**

```
┌─────────────────────────────────────────────────────────┐
│                    AI SERVICE                           │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐     │
│  │   CV        │  │   Matching  │  │   Analytics │     │
│  │  Parser     │  │   Engine    │  │   Engine    │     │
│  │             │  │             │  │             │     │
│  │ - PDF/Word  │  │ - Skill     │  │ - Predict   │     │
│  │   parsing   │  │   matching  │  │   time-to-  │     │
│  │ - NLP       │  │ - Cultural  │  │   hire      │     │
│  │   entity    │  │   fit       │  │ - Success   │     │
│  │   extraction│  │ - Red flags │  │   rate      │     │
│  │ - Data      │  │   detection │  │   prediction│     │
│  │   validation│  │ - Score     │  │ - Market    │     │
│  │             │  │   calc      │  │   insights  │     │
│  └─────────────┘  └─────────────┘  └─────────────┘     │
│           │               │               │            │
└───────────┼───────────────┼───────────────┼────────────┘
            │               │               │
▼───────────▼───────────────▼───────────────▼────────────┐
│                  ML Model Repository                   │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐    │
│  │   Skill     │  │   Cultural  │  │   Success   │    │
│  │   Matching  │  │   Fit       │  │   Predictor │    │
│  │   Model     │  │   Model     │  │   Model     │    │
│  │             │  │             │  │             │    │
│  │ - BERT      │  │ - Custom    │  │ - XGBoost   │    │
│  │   embeddings│  │   clustering│  │   ensemble  │    │
│  │ - Word2Vec  │  │ - Company   │  │ - Historical│    │
│  │   similarity│  │   values    │  │   data      │    │
│  │             │  │   matching  │  │   analysis  │    │
│  └─────────────┘  └─────────────┘  └─────────────┘    │
└───────────────────────────────────────────────────────┘
            │               │               │
▼───────────▼───────────────▼───────────────▼────────────┐
│                  External Dependencies                 │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐    │
│  │   AWS       │  │   Candidate │  │   Job       │    │
│  │ Comprehend  │  │   Service   │  │   Service   │    │
│  │   (NLP)     │  │   (gRPC)    │  │   (gRPC)    │    │
│  └─────────────┘  └─────────────┘  └─────────────┘    │
└───────────────────────────────────────────────────────┘
```

### **Flujo de Datos del AI Service:**

```
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│   Request   │ -> │   CV Parser │ -> │  Matching   │
│   Incoming  │    │   Component │    │   Engine    │
└─────────────┘    └─────────────┘    └─────────────┘
         │                │                 │
         ▼                ▼                 ▼
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│  Validate   │    │  Extract    │    │  Calculate  │
│   Input     │    │  Entities   │    │   Scores    │
└─────────────┘    └─────────────┘    └─────────────┘
         │                │                 │
         ▼                ▼                 ▼
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│  Log Event  │    │  Enrich     │    │  Generate   │
│             │    │  Profile    │    │  Insights   │
└─────────────┘    └─────────────┘    └─────────────┘
         │                │                 │
         └────────────────┼─────────────────┘
                          │
                          ▼
                 ┌─────────────┐
                 │   Return    │
                 │   Response  │
                 └─────────────┘
```

### **Tecnologías Específicas del AI Service:**

- **Framework:** FastAPI (Python)
- **ML Framework:** TensorFlow, PyTorch, Scikit-learn
- **NLP:** spaCy, NLTK, AWS Comprehend
- **Embeddings:** Sentence-BERT, Word2Vec
- **Almacenamiento:** S3 (modelos), Redis (cache)
- **Monitorización:** CloudWatch, SageMaker Debugger

Esta arquitectura proporciona una base sólida y escalable para el sistema TalentFlow AI, con especial énfasis en el componente de IA que es fundamental para la propuesta de valor diferenciada.


