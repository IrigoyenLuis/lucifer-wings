# 🪽 Lucifer’s Wings 🪽

**Lucifer’s Wings** es un simulador de exámenes interactivo diseñado para estudiar de forma **dinámica, clara y personalizada**.  
Incluye un **simulador de exámenes** para estudiantes y un **editor visual** que permite crear y modificar exámenes **sin necesidad de saber aspectos técnicos (Json, etc.)**.

El objetivo es que cualquier persona pueda **estudiar, practicar y crear exámenes** de manera sencilla, ordenada y confiable.

---

## 🎓 Enfoque en certificaciones y exámenes reales

Lucifer’s Wings está pensado para la **preparación de exámenes de certificación y evaluaciones formales**, como:

- Exámenes tipo **EGEL Plus**
- Certificaciones técnicas y profesionales 
- Certificaciones de Idiomas
- Evaluaciones universitarias y académicas
- Estudio autodidacta
- Pruebas de conocimientos y retos personales
- Cisco

El sistema utiliza una estructura de preguntas **similar a la de certificaciones reales**, incluyendo:

- Reactivos por secciones
- Preguntas de opción múltiple (una o varias respuestas correctas)
- Uso de imágenes en preguntas
- Resultados claros y medibles

⚠️ **Lucifer’s Wings no sustituye un examen oficial**, pero permite entrenar en un entorno muy cercano al real, ayudando a:

- Reducir la ansiedad del examen
- Medir el nivel de preparación
- Detectar áreas débiles
- Practicar bajo un formato similar al de las examinaciones reales

---

## 🚀 Avances recientes (Versiones 1.4 y 1.5)

### Versión 1.4
- Soporte estable para preguntas de opción múltiple con **una o varias respuestas correctas**.
- Sistema básico de **validación** y resultados más claros en el simulador.

### Versión 1.5
- Se añadió el tipo de reactivo **`respuesta_corta(Es decir respuesta breve)`**.
- Se admiten respuestas abiertas, tanto sensibles a mayusculas, como no sensibles. 
- El editor gestiona automáticamente los tipos de pregunta.
- Validación más estricta, con advertencias de consistencia académica entendibles.
- Mejor manejo de imágenes y ajustes finos en la interfaz.

Estas versiones marcan el paso de un simulador universal de examenes a una herramienta de **entrenamiento real**.

---

## 📦 ¿Qué incluye este paquete?

En la carpeta encontrarás los siguientes elementos:

- **LucifersWings.exe**  
  👉 Simulador de exámenes (uso principal para estudiantes).

- **LW_Editor.exe**  
  👉 Editor visual para crear y editar exámenes sin escribir JSON.

- **LW_EscritorioAccesosDirectos.exe**  
  👉 Utilidad opcional que crea accesos directos en el escritorio.

- **MisExamenes/**  
  👉 Carpeta donde se guardan todos los exámenes disponibles.

- **sonidos/**  
  👉 Carpeta con los sonidos del sistema (personalizables).

---

## ▶️ Lucifer’s Wings – Simulador de Exámenes

Este es el programa que usarás para **presentar exámenes**.

### Cómo usarlo

1. Abre **LucifersWings.exe**.
2. Asegúrate de que tus exámenes estén dentro de la carpeta **MisExamenes/**.
3. Selecciona un examen desde la lista.
4. Inicia el examen y responde las preguntas.
5. Al finalizar, verás:
   - Puntaje obtenido
   - Resumen de respuestas
   - Posibilidad de guardar tu nombre en el **highscore**

### Características principales

- Interfaz clara y enfocada en el examen
- Soporte para preguntas con imagen
- Preguntas de opción múltiple (una o varias respuestas correctas)
- Aleatorización de preguntas por sección
- Sistema de puntaje y resultados
- Guardado de highscores por examen

---

## ✏️ LW Editor – Editor Visual de Exámenes

El **Editor** está pensado para **docentes, creadores de contenido o estudiantes avanzados** que quieran crear sus propios exámenes **sin tocar archivos JSON** salvo que disfruten hacerlo.

### ¿Qué problema resuelve?

Normalmente, crear un examen en JSON hecho "a mano" es:

- Difícil
- Propenso a errores
- Poco amigable

👉 **LW Editor elimina todo eso.**

### Qué puedes hacer con el Editor

- Crear un examen nuevo desde cero
- Editar exámenes existentes
- Agregar, modificar o eliminar preguntas
- Definir:
  - Área
  - Sección
  - Opciones A, B, C, D
  - Una o varias respuestas correctas
- Agregar imágenes a las preguntas
- Validar automáticamente la estructura del examen
- Guardar sin romper el formato interno

### Flujo típico

1. Abre **LW_Editor.exe**.
2. Elige una opción:
   - **Crear nuevo examen**
   - **Editar examen**
   - **Validar examen**
3. Trabaja visualmente con botones y campos.
4. Guarda y listo: el examen ya funciona en el simulador.

> 💡 El editor se encarga de mantener la estructura correcta del examen por ti.

---

## 🖼 Imágenes en preguntas

- Las imágenes se guardan automáticamente en la carpeta `recursos/` del examen.
- Puedes:
  - Agregar una imagen nueva
  - Vincular una imagen existente
  - Quitar el vínculo
  - Eliminar imágenes no usadas
- Todo se gestiona desde botones, **sin tocar archivos a mano**.

---

## 🔊 Sonidos del sistema

Dentro de la carpeta **sonidos/** puedes encontrar los audios del sistema.

### ¿Se pueden cambiar?
✅ Sí.

- Puedes reemplazar los archivos de sonido por otros.
- Mantén el mismo nombre de archivo.
- Usa archivos **`.wav`** para asegurar compatibilidad.

⚠️ Actualmente el sistema solo admite archivos `.wav`.

---

## 📁 Estructura recomendada de exámenes

Cada examen vive dentro de su propia carpeta en **MisExamenes/**:

```text
MisExamenes/
 └── MiExamen/
     ├── examen.json
     ├── recursos/
     └── highscores.json



