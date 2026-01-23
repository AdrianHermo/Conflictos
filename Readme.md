# Práctica Git: Conflictos y Resolución

## Paso 1: Sincronización de la Mente Maestra

**Pregunta 1:** ¿Por qué es necesario realizar un "clone" al inicio en lugar de simplemente copiar el archivo manualmente?  
- Porque con `git clone` tenemos el proyecto completo con historial, ramas y conexión al repositorio. Copiar archivos solo nos da el código.

**Pregunta 2:** En PyCharm, ¿qué indicador visual te confirma que tu proyecto está vinculado correctamente a un repositorio Git?  
- Que aparece el nombre de la rama abajo a la derecha y que el menú Git está activo.

---

## Paso 2: El Sabotaje Creativo

**Pregunta 1:** ¿Qué ocurre exactamente al hacer un push si alguien ya realizó y subió un cambio en la misma zona del código?  
- Git rechaza el push porque no tenemos los cambios del otro y no puede sobrescribirlos automáticamente.

**Pregunta 2:** ¿Por qué Git no decide automáticamente que el último push es el válido?  
- Porque Git no sabe cuál cambio es correcto y sobrescribir podría borrar trabajo de alguien más.

---

## Paso 3: La Resolución del Alquimista

**Pregunta 1:** ¿Cómo definirías un "conflicto" en Git basándote en lo que acabas de ver en la herramienta de PyCharm?  
- Es cuando dos cambios modifican la misma línea y Git no puede decidir cuál queda.

**Pregunta 2:** ¿Qué pasos debes seguir en el IDE tras aceptar los cambios para que la resolución sea definitiva en el repositorio remoto?  
- Guardar el archivo, hacer commit del merge y luego hacer push.

---

## Paso 4: El Arte de la Conexión

**Pregunta 1:** ¿Qué estrategia o flujo de trabajo (workflow) consideráis más efectivo para evitar conflictos constantes en un equipo grande?  
- Trabajar por ramas (feature branches), usar pull requests y revisar antes de mergear. Así nadie toca la rama principal directamente.

---

