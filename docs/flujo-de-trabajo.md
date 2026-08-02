# Flujo de trabajo y registro de comandos

## Secuencia de trabajo y riesgos que evita cada paso

1. **Crear repositorio**  
   Evita trabajar sin un lugar centralizado y organizado.

2. **Crear rama**  
   Evita modificar directamente main y dañar la versión estable.

3. **Hacer commits**  
   Evita perder el historial de cambios y permite volver atrás si es necesario.

4. **Abrir pull request**  
   Evita fusionar cambios sin revisión.

5. **Revisar**  
   Evita introducir errores o documentación incompleta.

6. **Corregir observaciones**  
   Evita dejar problemas sin resolver antes de fusionar.

7. **Fusionar**  
   Integra los cambios de forma controlada y segura en main.

## Registro de comandos observados en Learn Git Branching

### git commit
Se crea un nuevo nodo (commit) y la rama actual se mueve para apuntar a ese nuevo nodo.

### git branch
Se crea una nueva rama que apunta al mismo commit en el que se encontraba la rama actual.

### git checkout
Se cambia de rama. El puntero HEAD se mueve a la rama seleccionada y el estado del proyecto cambia al de esa rama.

### git merge
Se integran las historias de dos ramas. Los commits de una rama se combinan con la otra.
