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

**Ejemplo de uso:**
> Juan estudió 4 veces esta semana, cada sesión duró 2 horas. El lunes estudió gramática, el miércoles practicó pronunciación, el viernes estudió vocabulario y el domingo practicó listening.

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

## Estructura del Proyecto

```
prlest-final/
├── backend/          # API Django
├── frontend/         # Aplicación Angular
├── docker-compose.yml
└── README.md
```

## Próximos Pasos

1. Configuración inicial del proyecto
2. Implementación de autenticación SSO
3. Desarrollo de funcionalidades core
4. Implementación del sistema de gamificación
5. Creación de dashboards de análisis
6. Despliegue en servidor universitario

---

**Desarrollado para**: Departamento de Lenguas Extranjeras y Departamento de Estadística  
**Propósito**: Seguimiento de hábitos de aprendizaje de idiomas con gamificación y análisis de datos
