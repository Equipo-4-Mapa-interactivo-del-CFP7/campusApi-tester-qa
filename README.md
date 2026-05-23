# campusApi-tester-qa

Proyecto de QA y testing automatizado para CampusMap - Equipo 4 CFP7

## Equipo QA
- Priscila
- Jairo
- María

## Tecnologías
- Node.js
- WebdriverIO
- Mocha
- Cucumber / Gherkin

## Estructura
test/
├── features/          → escenarios en Gherkin
├── step-definitions/  → código JS de cada paso
├── page-objects/      → elementos de cada página
└── specs/             → tests con Mocha

## Cómo correr los tests
npm run wdio

---

## Features principales
- Login
- Buscador
- Mapa interactivo
- Recorridos
- Reportes
- Accesibilidad
- Responsive / Mobile

---
## Flujos funcionales principales
- Buscar un espacio
- Visualizar información de un sector
- Consultar un recorrido
- Reportar un incidente o barrera

---
## Consideraciones de accesibilidad, usabilidad y experiencia
### Navegación y experiencia de uso
- ¿Va a ser necesario login para navegar?
- ¿La navegación puede mantenerse simple y clara para personas con ansiedad o que se desorienten fácilmente?
- ¿La interfaz sería fácil de usar para personas mayores?
- Evitar exceso de información visual o demasiados pasos.
- Mantener mapas simples y fáciles de interpretar.
- No saturar la interfaz con demasiados botones o elementos.
- Usar mensajes claros y lenguaje simple.

### Accesibilidad visual
- Buen contraste.
- Tipografía legible.
- Tamaños de texto cómodos.
- Íconos fáciles de comprender.

### Accesibilidad para discapacidad visual
- Considerar soporte para lectores de pantalla.
- Pensar indicadores de audio o navegación asistida.
- Verificar si la interfaz sigue siendo usable sin sonido.

### Conectividad
- Pensar si algunas funciones podrían mantenerse accesibles sin conexión una vez cargadas.