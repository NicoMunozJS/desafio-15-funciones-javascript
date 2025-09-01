📌 Desafío 4 - Funciones
Este proyecto corresponde al Desafío 3 del bootcamp Desafío Latam.  
El objetivo es validar conocimientos en **transformación y modificación de funciones** y la manipulación de eventos y DOM en JavaScript.

🚀 Objetivo del desafío
- Transformar funciones tradicionales a expresiones y arrow functions.
- Modificar el comportamiento de funciones que interactúan con elementos HTML.
- Crear páginas web interactivas que respondan a eventos de click y teclado.
- Aplicar la lógica de eventos y funciones para manipular colores dinámicamente.

✅ Requerimientos cumplidos
1. **Funciones**
   - Transformación de funciones tradicionales a funciones de expresión (`1_funcion.js`).
   - Transformación a arrow functions de una línea (`2_arrow.js`).

2. **Cambiar color de fondo al click**
   - `pintar.html` y `script.js` implementados.
   - La función recibe el elemento clickeado como argumento.
   - Posibilidad de pasar un color por parámetro (verde por defecto, amarillo al hacer click).

3. **4_colores.html**
   - Cuatro divs con colores iniciales (azul, rojo, verde y amarillo).
   - Al hacer click, cambian de color a negro.
   - Se utiliza `addEventListener` para asignar los eventos.

4. **Evento de teclado**
   - Variable global que guarda un color dependiendo de la tecla presionada.
     - `a` → rosado  
     - `s` → naranjo  
     - `d` → celeste  
   - Nuevo div con id `key` de 200px x 200px cambia de color según la tecla.
   - Teclas `q`, `w` y `e` crean nuevos divs de colores morado, gris y café respectivamente.

🛠️ Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript (Funciones, Eventos, DOM)
- Git para control de versiones

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/imignaciotwentythree/funciones.git
