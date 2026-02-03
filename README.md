# Calorie Tracker

Aplicación React + TypeScript + Vite que permite registrar comidas y ejercicios para controlar calorías consumidas, quemadas y netas. Usa un reducer propio para centralizar el estado, persiste activitates en _LocalStorage_ y ofrece edición/eliminación directa desde la interfaz.

## Características Principales

1. **Formulario dinámico:** Crea o edita actividades (categoría, nombre y calorías) validando entradas y generando IDs únicos.
2. **Gestión global con reducer:** Maneja alta/edición, selección activa, borrado y reinicio de la app; inicializa estado desde _LocalStorage_.
3. **Resumen visual de calorías:** Cálculos para calorías consumidas, quemadas y diferencia neta con presentación clara.
4. **Listado interactivo:** Muestra cada actividad con etiqueta de categoría y acciones para editar o eliminar.
5. **Persistencia automática y reinicio:** Sincroniza el estado en _LocalStorage_ y permite reiniciar la aplicación cuando hay datos.
