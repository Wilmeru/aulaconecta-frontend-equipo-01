# Conceptos de Git y GitHub

## 1. ¿Qué puede hacer Git aunque GitHub no exista?
Git puede registrar todos los cambios de un proyecto en el computador local, crear ramas, hacer commits y volver a versiones anteriores sin necesidad de internet ni de GitHub.

## 2. ¿Por qué una rama reduce el riesgo de dañar main?
Porque permite trabajar y probar cambios en una línea separada. Si algo sale mal, main permanece intacta y se puede descartar la rama sin afectar la versión principal.

## 3. ¿Qué diferencia existe entre guardar un archivo y crear un commit?
Guardar un archivo solo actualiza el archivo en el computador. Crear un commit registra ese cambio en el historial de Git con un mensaje que explica qué se hizo y quién lo hizo.

## 4. ¿Por qué un pull request no es lo mismo que un merge?
Un pull request es una solicitud para que alguien revise los cambios. El merge es la acción final de integrar esos cambios en otra rama después de la revisión.

## 5. ¿Qué evidencia permite saber quién cambió algo y por qué?
El historial de commits. Cada commit muestra el autor, la fecha y el mensaje que explica el motivo del cambio.

## Secuencia de trabajo recomendada

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
