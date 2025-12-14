LUCIFER WINGS
Simulador de exámenes tipo EGEL Plus

--------------------------------------------------
1. ¿QUÉ ES LUCIFER WINGS?
--------------------------------------------------

Lucifer Wings es un simulador de exámenes inspirado en la
estructura y dinámica del EGEL Plus.

Permite practicar bajo condiciones reales:
- Examen por secciones
- Temporizador independiente por sección
- Calificación automática
- Nivel de desempeño
- Historial de mejores puntajes (highscores)

No es un examen oficial de CENEVAL.
Es una herramienta de práctica y autoevaluación.

--------------------------------------------------
2. CÓMO JUGAR (USO NORMAL)
--------------------------------------------------

1) Ejecuta el archivo:
   LuciferWings.exe

2) Selecciona una carrera o examen disponible.

3) Elige el tiempo por sección:
   - 30 minutos
   - 1 a 4 horas

4) Responde las preguntas.
   - Selecciona A, B, C o D
   - Avanza con el botón "Siguiente"

5) Al finalizar:
   - Revisa tu porcentaje
   - Observa tu nivel de desempeño
   - Guarda tu puntaje si lo deseas

--------------------------------------------------
3. CARPETA "MisExamenes"
--------------------------------------------------

Lucifer Wings carga los exámenes desde la carpeta:

   MisExamenes/

Cada subcarpeta representa un examen o carrera.

Ejemplo:

MisExamenes/
 ├─ ISOFT/
 │   └─ examen.json
 ├─ PSICOLOGIA/
 │   └─ examen.json
 ├─ NUTRIOLOGIA/
 │   └─ examen.json
 └─ DERECHO/
     └─ examen.json

El nombre de la carpeta es el nombre que verá el usuario.

--------------------------------------------------
4. CREAR TUS PROPIOS EXÁMENES (USUARIO AVANZADO)
--------------------------------------------------

Lucifer Wings permite cargar exámenes personalizados
usando archivos en formato JSON.

Para crear un examen nuevo:

1) Copia una carpeta existente dentro de "MisExamenes".
2) Cambia el nombre de la carpeta.
3) Edita el archivo "examen.json".

El archivo debe seguir EXACTAMENTE la estructura del
archivo de plantilla incluido.

--------------------------------------------------
5. ESTRUCTURA DEL ARCHIVO examen.json
--------------------------------------------------

Campos obligatorios del examen:

- versionSchema: "1.0"
- idExamen
- nombreExamen
- disciplina
- reactivos

Cada reactivo debe incluir:

- tipoReactivo: "estandar" o "multireactivo"
- idReactivo
- area: "Disciplinar" o "Transversal"
- seccion: 1 o 2
- planteamiento
- opciones (A, B, C, D)
- respuestaCorrecta

Opcionalmente, se pueden incluir imágenes u otros
recursos visuales dentro de la carpeta del examen.

--------------------------------------------------
6. VALIDACIÓN
--------------------------------------------------

Si un examen tiene errores de estructura, el programa
lo marcará como inválido y no permitirá iniciarlo.

Esto es normal y sirve para evitar fallos durante el examen.

--------------------------------------------------
7. NOTAS IMPORTANTES
--------------------------------------------------

- No modifiques los archivos internos del programa.
- No cambies los nombres de los campos del JSON.
- Usa siempre letras A, B, C y D en las opciones.
- El programa no requiere instalación.

--------------------------------------------------
Autor: Luis Irigoyen
Licencia: CC BY-NC-ND 4.0
