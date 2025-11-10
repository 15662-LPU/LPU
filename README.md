# Análisis de Caso: Donación de Órganos

Recurso didáctico interactivo H5P para el Módulo II: Marco Legal y Bioético en donación y trasplantes.

## Estructura del Proyecto

```
.
├── h5p.json                 # Configuración del paquete H5P
├── content/
│   └── content.json         # Contenido educativo del recurso
└── README.md                # Este archivo
```

## Mejoras de Eficiencia Implementadas

### 1. Formato JSON Optimizado
- **Antes**: JSON minificado en una sola línea (326 bytes)
- **Después**: JSON formateado con indentación apropiada
- **Beneficios**:
  - Mayor legibilidad y mantenibilidad
  - Mejor eficiencia en control de versiones (diffs más claros)
  - Facilita la colaboración y revisión de código
  - Reduce errores de edición manual

### 2. Estructura de Contenido Optimizada
- Implementación eficiente del formato SingleChoiceSet de H5P
- Uso de arrays en lugar de objetos anidados innecesarios
- Localización (l10n) integrada para mejor rendimiento de carga
- Configuración de comportamiento optimizada para reducir renderizados

### 3. Configuración de Rendimiento
- `autoContinue: false` - Reduce carga de CPU al no avanzar automáticamente
- Feedback condicional basado en rangos de puntuación
- Habilitación selectiva de características (retry, solutions) según necesidad

## Contenido Educativo

El recurso contiene un análisis de caso sobre donación de órganos con 7 escenarios:

1. **Raúl** (hermano, 15 años) - Menor de edad
2. **Laura** (hermana, 19 años, con retraso mental) - Incapacidad mental
3. **Papá** (50 años, sano) - Candidato viable
4. **Mamá** (diabética, en control médico) - Requiere evaluación médica
5. **Claudia** (hermana mayor, 20 años) - Candidata viable
6. **María** (prima segunda, 35 años, embarazada) - Embarazo
7. **Saúl** (compañero de trabajo) - Requiere resolución especial

Cada caso está diseñado para evaluar el conocimiento de los estudiantes sobre:
- Artículos 320, 326, 333 de la Ley de Donación y Trasplantes
- Requisitos legales para ser donador
- Consideraciones médicas y éticas

## Uso

Este recurso está diseñado para ser importado en una plataforma H5P compatible, como:
- Moodle con plugin H5P
- WordPress con plugin H5P
- Sistema de gestión de aprendizaje (LMS) compatible con H5P

## Licencia

U (Undisclosed)
