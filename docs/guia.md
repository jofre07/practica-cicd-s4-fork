# Guía del Proyecto

## Descripción

TaskManager es una aplicación simple de gestión de tareas desarrollada como proyecto de práctica para el módulo MDW101 - Control de Versiones.

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/[usuario]/practica-cicd-s4.git

# Entrar al directorio
cd practica-cicd-s4

# Ejecutar tests
npm test
```

## Uso

```javascript
const TaskManager = require('./src/app');

const manager = new TaskManager();

// Agregar tareas
manager.addTask('Mi primera tarea', 'alta');
manager.addTask('Otra tarea', 'media');

// Completar una tarea
manager.completeTask(1);

// Ver estadísticas
console.log(manager.getStats());
```

## Estructura del Proyecto

- `src/` - Código fuente
- `tests/` - Tests unitarios
- `docs/` - Documentación

## Contribuir

1. Crear una rama feature
2. Hacer cambios
3. Crear Pull Request

## Licencia

MIT
