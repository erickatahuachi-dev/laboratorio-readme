# Laboratorio README 
Proyecto de práctica para aprender Markdown avanzado en GitHub. 
## Descripción 
Este repositorio documenta paso a paso mi aprendizaje de Markdown: 
tablas, listas de tareas, badges y diagramas.
## Estado de funcionalidades 
| Función | Estado | 
|----------|-------------| 
| Login | Listo | 
| Reportes | En progreso |
## Pendientes 
- [x] Diseño de la base de datos 
- [ ] Pruebas unitarias
![Estado](https://img.shields.io/badge/build-passing-brightgreen)
## Arquitectura 
```mermaid 
graph LR 
 A[Usuario] --> B[Frontend] 
 B --> C[API] 
 C --> D[(Base de datos)] 
```
git add README.md 
git commit -m "Agrega tabla, checklist, badge y diagrama al README" 
git push
