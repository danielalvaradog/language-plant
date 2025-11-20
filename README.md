# Tracker de Aprendizaje de Idiomas con Gamificación

## Descripción General

Esta aplicación es un sistema de seguimiento de hábitos de aprendizaje de idiomas diseñado específicamente para uso universitario. La aplicación combina el registro de sesiones de estudio con un elemento de gamificación (cuidado de una planta virtual) para motivar a los estudiantes a mantener una práctica constante de idiomas.

## ¿Qué hace la aplicación?

### Para Estudiantes

La aplicación permite a los estudiantes registrar sus sesiones de estudio de idiomas de manera sencilla e intuitiva. Cada sesión incluye:

- **Fecha y duración**: Cuándo y cuánto tiempo estudió el estudiante
- **Idioma**: Qué idioma está aprendiendo (inglés, francés, alemán, etc.)
- **Tipo de práctica**: Qué aspecto del idioma practicó:
  - Gramática
  - Pronunciación
  - Vocabulario
  - Comprensión auditiva (listening)
  - Lectura
  - Escritura
  - Conversación
- **Fuente/Material**: Qué recurso utilizó para estudiar (opcional):
  - Libro específico (ej: "Libro de gramática avanzada")
  - Video de YouTube o plataforma externa
  - Material del aula virtual
  - Contenido de la propia aplicación
  - Clase presencial o virtual
  - Aplicación externa (Duolingo, Anki, etc.)
  - Práctica de conversación
- **Notas**: Comentarios opcionales sobre qué aprendió o practicó

**Ejemplo de uso:**
> Juan estudió 4 veces esta semana, cada sesión duró 2 horas. El lunes estudió gramática usando el libro "English Grammar in Use", el miércoles practicó pronunciación con un video de YouTube, el viernes estudió vocabulario usando las flashcards de la app, y el domingo practicó listening con material del aula virtual.

### Sistema de Gamificación: La Planta Virtual

Para motivar a los estudiantes a mantener una práctica constante, la aplicación incluye una planta virtual que:

- **Crece y se mantiene saludable** cuando el estudiante registra sesiones de estudio regularmente
- **Se deteriora** si el estudiante no estudia durante varios días consecutivos
- **Evoluciona** a través de diferentes etapas (semilla, brote, joven, madura, florecida) según el compromiso del estudiante
- **Refleja el progreso** del estudiante de manera visual y motivacional

La salud de la planta se calcula basándose en:
- Frecuencia de estudio (cuántas veces por semana)
- Duración de las sesiones
- Consistencia (días consecutivos estudiando)
- Total de días de estudio acumulados

### Contenido Educativo Integrado

La aplicación incluye una biblioteca de contenido educativo que complementa el tracking de sesiones:

#### Biblioteca de Materiales

El contenido educativo puede provenir de múltiples fuentes:

- **Creado por profesores**: Los profesores de lenguas pueden subir y compartir materiales propios
- **Generado con IA**: Contenido educativo generado automáticamente usando LLM (ejercicios, explicaciones, ejemplos)
- **Fuentes externas**: Enlaces y referencias a materiales que los profesores ya utilizan en sus clases
- **Contenido colaborativo**: Materiales compartidos entre profesores y estudiantes

#### Tipos de Contenido Disponibles

- **Vocabulario**: Sistema de flashcards con repetición espaciada (estilo Anki)
  - Decks personalizados por idioma y nivel
  - Generación automática de flashcards con LLM
  - Integración con el tracking: estudiar flashcards cuenta como sesión de estudio
  
- **Gramática**: Ejercicios interactivos con explicaciones contextualizadas
  - Ejercicios generados con IA adaptados al nivel del estudiante
  - Explicaciones claras y ejemplos relevantes
  
- **Pronunciación**: Práctica con reconocimiento de voz (futuro)
  - Ejercicios de pronunciación interactivos
  
- **Comprensión auditiva**: Audio con ejercicios de comprensión
  - Materiales de audio con preguntas asociadas
  
- **Lectura**: Textos con ejercicios de comprensión lectora
  - Textos adaptados al nivel con ejercicios de comprensión
  
- **Escritura**: Ejercicios con feedback automático (futuro)
  - Práctica de escritura con corrección asistida

#### Generación de Contenido con IA

Una ventaja clave de la aplicación es la capacidad de generar contenido educativo personalizado usando LLM:

- **Ejercicios adaptados**: Contenido personalizado según el nivel del estudiante
- **Explicaciones contextualizadas**: Explicaciones claras adaptadas al contexto de aprendizaje
- **Ejemplos relevantes**: Ejemplos variados y contextualizados
- **Múltiples idiomas**: Generación de contenido en diferentes idiomas sin traducción manual
- **Escalabilidad**: Capacidad de generar grandes cantidades de contenido educativo de forma eficiente

### Para Profesores de Lenguas

Los profesores tienen acceso a funcionalidades especiales para crear y gestionar contenido educativo:

1. **Crear y compartir contenido**
   - Subir materiales propios (ejercicios, textos, audio, videos)
   - Generar contenido usando IA asistida
   - Compartir recursos con sus estudiantes o con otros profesores
   - Crear bibliotecas compartidas por idioma o nivel

2. **Monitorear el uso de contenido**
   - Ver qué materiales son más populares entre los estudiantes
   - Identificar qué contenido ayuda más al aprendizaje
   - Ajustar recursos según feedback de uso y datos de engagement

3. **Colaborar con otros profesores**
   - Compartir materiales entre colegas
   - Crear repositorios compartidos de contenido educativo
   - Coordinar la creación de contenido para diferentes niveles

4. **Analytics de estudiantes** (opcional)
   - Ver patrones de estudio de estudiantes que usan la app
   - Identificar estudiantes que pueden necesitar apoyo adicional
   - Entender qué tipos de práctica prefieren los estudiantes

## Beneficios para las Facultades

### Facultad de Idiomas Extranjeros

La aplicación proporciona datos valiosos que ayudan a la facultad a:

1. **Entender los intereses de los estudiantes**
   - Identificar qué tipos de práctica son más populares entre los estudiantes
   - Detectar áreas donde los estudiantes muestran más interés o motivación
   - Comprender las preferencias de aprendizaje de los estudiantes

2. **Identificar áreas de mejora**
   - Reconocer qué aspectos del idioma necesitan más atención (por ejemplo, si pocos estudiantes practican pronunciación)
   - Detectar patrones de estudio que pueden indicar dificultades en áreas específicas
   - Ajustar el currículo y los recursos educativos según las necesidades reales

3. **Monitorear el compromiso estudiantil**
   - Evaluar la frecuencia y consistencia del estudio de los estudiantes
   - Identificar estudiantes que pueden necesitar apoyo adicional
   - Medir el impacto de diferentes estrategias de enseñanza

4. **Tomar decisiones basadas en datos**
   - Planificar cursos y talleres según las necesidades identificadas
   - Asignar recursos educativos de manera más efectiva
   - Evaluar la efectividad de programas y metodologías

### Facultad de Estadística

La aplicación ofrece una fuente rica de datos para investigación y análisis:

1. **Datos agregados y anonimizados**
   - Exportación de datos en formatos CSV/JSON para análisis estadístico
   - Datos completamente anonimizados (sin información personal identificable)
   - Filtros por rango de fechas, idioma y tipo de práctica

2. **Métricas disponibles para análisis**
   - Frecuencia promedio de estudio por semana
   - Duración promedio de las sesiones de estudio
   - Distribución de tipos de práctica
   - Popularidad de diferentes idiomas
   - Patrones temporales de estudio (días de la semana, horas, etc.)
   - Correlaciones entre diferentes variables de aprendizaje

3. **Oportunidades de investigación**
   - Estudios sobre hábitos de aprendizaje de idiomas
   - Análisis de efectividad de gamificación en educación
   - Investigación sobre motivación estudiantil
   - Modelos predictivos de éxito en aprendizaje de idiomas
   - Análisis de series temporales de comportamiento estudiantil

4. **Dashboards y visualizaciones**
   - Acceso a dashboards con gráficos y visualizaciones
   - Herramientas para explorar los datos de manera interactiva
   - Capacidad de generar reportes personalizados

## Características Técnicas

### Arquitectura

- **Base de datos**: PostgreSQL (alojada en el servidor de la universidad)
- **Backend**: Django (API REST con autenticación SSO universitaria)
- **Frontend**: Angular (interfaz de usuario moderna y responsiva)
- **Despliegue**: Docker (contenedores para fácil instalación en el servidor universitario)

### Seguridad y Privacidad

- Autenticación mediante SSO de la universidad
- Datos de estudiantes completamente anonimizados para exportaciones
- Roles y permisos diferenciados (estudiante, facultad, administrador)
- Protección contra inyección SQL y otros ataques comunes
- Cumplimiento con políticas de privacidad de datos universitarios

### Escalabilidad

La aplicación está diseñada para:
- Escalar a cientos o miles de estudiantes
- Agregar nuevos idiomas fácilmente
- Expandirse con componentes de práctica interactivos en el futuro
- Integrarse con otros sistemas universitarios si es necesario

## Integración con Aulas Virtuales Universitarias

### Enfoque Complementario

Esta aplicación está diseñada para **complementar**, no reemplazar, las aulas virtuales existentes de la universidad. La división de responsabilidades es clara:

**Aulas Virtuales (existente):**
- Gestión formal de cursos y matriculación
- Materiales oficiales de clase
- Tareas y evaluaciones
- Calificaciones y notas
- Comunicación formal profesor-estudiante

**Esta Aplicación (complementaria):**
- Tracking de hábitos de estudio autónomo
- Práctica complementaria voluntaria
- Gamificación y motivación personal
- Análisis de patrones de aprendizaje
- Contenido de práctica adicional (no necesariamente evaluativo)

### Características de Integración

1. **Acceso opcional desde aulas virtuales**
   - Enlace o widget opcional en el aula virtual que redirige a esta app
   - No interfiere con el flujo normal de las clases
   - Los profesores pueden sugerir su uso, pero no es obligatorio

2. **Registro de sesiones con contexto opcional**
   - Los estudiantes pueden vincular sesiones de práctica con cursos específicos (opcional)
   - Permite identificar si estudiaron material del aula virtual o práctica independiente
   - Campo opcional para indicar "Estudié para el curso X" o "Usé material del aula virtual"
   - No requiere gestión adicional por parte de los profesores

3. **Contenido complementario, no duplicado**
   - No duplica materiales del aula virtual
   - Ofrece práctica adicional y ejercicios complementarios
   - Contenido generado con IA para práctica autónoma
   - Los estudiantes pueden practicar cualquier idioma, no solo los de cursos matriculados

4. **Independencia técnica**
   - Funciona de forma independiente del sistema de aulas virtuales
   - Comparte solo autenticación SSO (ya implementado)
   - No requiere integración compleja ni cambios en el sistema existente
   - API opcional para leer cursos matriculados (solo lectura, futuro)

### Beneficios para Profesores

- **Sin carga adicional**: Los profesores no necesitan gestionar nada en esta app si no lo desean
- **Visibilidad opcional**: Pueden ver analytics de práctica complementaria si lo desean
- **Herramienta de apoyo**: Pueden sugerir su uso a estudiantes que necesiten práctica extra
- **Datos útiles**: Información sobre hábitos de estudio sin interferir con la gestión de cursos
- **Contenido flexible**: Pueden crear contenido de práctica adicional sin duplicar materiales del curso

### Beneficios para Estudiantes

- **Práctica flexible**: Pueden practicar cualquier idioma, no solo los de cursos matriculados
- **Motivación adicional**: Gamificación y tracking personal sin presión académica
- **Complemento voluntario**: No es obligatorio, solo una herramienta de apoyo
- **Práctica autónoma**: Pueden estudiar independientemente de los cursos formales
- **Tracking completo**: Registran tanto estudio formal como práctica independiente

## Diferenciación con Duolingo y Otras Plataformas

### ¿En qué se diferencia de Duolingo?

Esta aplicación se diferencia de Duolingo y otras plataformas comerciales en varios aspectos clave:

1. **Propósito y función**
   - **Duolingo**: Enseña idiomas mediante lecciones interactivas dentro de la app
   - **Esta app**: Registra y rastrea sesiones de estudio realizadas fuera de la app, además de ofrecer contenido complementario

2. **Enfoque de aprendizaje**
   - **Duolingo**: Contenido estructurado y método propio dentro de la plataforma
   - **Esta app**: Registro flexible de cualquier actividad de aprendizaje, complementado con contenido educativo generado con IA y creado por profesores

3. **Gamificación**
   - **Duolingo**: Streaks, XP, niveles, ligas, gemas
   - **Esta app**: Planta virtual que crece o se deteriora según consistencia y frecuencia del estudio

4. **Audiencia y contexto**
   - **Duolingo**: Público general, uso individual
   - **Esta app**: Estudiantes universitarios, integrada con sistemas universitarios (SSO), diseñada para uso institucional

5. **Análisis de datos**
   - **Duolingo**: Métricas principalmente para el usuario individual
   - **Esta app**: Datos agregados y anonimizados para facultades, análisis estadístico e investigación

6. **Integración institucional**
   - **Duolingo**: Aplicación independiente y comercial
   - **Esta app**: Integración con sistemas universitarios, roles diferenciados, despliegue en servidor universitario

7. **Flexibilidad pedagógica**
   - **Duolingo**: Método y contenido propios, estructura fija
   - **Esta app**: Agnóstica al método, permite que la universidad use sus propios recursos y metodologías, contenido generado con IA y creado por profesores

8. **Contenido multi-aspecto**
   - **Duolingo**: Enfoque principalmente en vocabulario y frases básicas
   - **Esta app**: Cubre todos los aspectos del idioma (gramática, pronunciación, vocabulario, listening, lectura, escritura, conversación)

9. **Contenido institucional**
   - **Duolingo**: Contenido genérico para público masivo
   - **Esta app**: Contenido creado/curated por profesores universitarios, adaptado a necesidades académicas específicas

### Ventajas Competitivas

- **Generación de contenido con LLM**: Contenido personalizado y adaptativo sin necesidad de traducción manual
- **Tracking + contenido**: Combina seguimiento de hábitos con práctica interactiva
- **Flexibilidad**: Permite usar materiales externos y propios
- **Enfoque académico**: Diseñado para complementar cursos universitarios
- **Sin costo para estudiantes**: Plataforma institucional sin suscripciones

## Estructura del Proyecto

```
prlest-final/
├── backend/          # API Django
├── frontend/         # Aplicación Angular
├── docker-compose.yml
└── README.md
```

## Próximos Pasos

### Fase 1: Fundamentos
1. Configuración inicial del proyecto
2. Implementación de autenticación SSO
3. Desarrollo de funcionalidades core de tracking
4. Implementación del sistema de gamificación (planta virtual)

### Fase 2: Contenido Educativo
5. Sistema de flashcards con repetición espaciada (estilo Anki)
6. Integración de generación de contenido con LLM
7. Panel para profesores (crear y compartir contenido)
8. Biblioteca de materiales educativos

### Fase 3: Análisis y Visualización
9. Creación de dashboards de análisis
10. Herramientas de exportación de datos
11. Visualizaciones para facultades

### Fase 4: Integración y Expansión
12. Integración opcional con aulas virtuales (enlace/widget)
13. Ejercicios interactivos adicionales (gramática, pronunciación, etc.)
14. Despliegue en servidor universitario
15. Pruebas piloto con estudiantes y profesores

---

**Desarrollado para**: Departamento de Lenguas Extranjeras y Departamento de Estadística  
**Propósito**: Seguimiento de hábitos de aprendizaje de idiomas con gamificación y análisis de datos
