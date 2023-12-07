# Tipos de Selectores
1. Selectores Simples
    * Selector universal: es un selector que ayuda a poder seleccionar todos los elementos del archivo html.
      ```css
      * {
        color: red;
      }
      ```
    * Selector de etiqueta: este selector nos ayuda a seleccionar solo las etiquetas que le indicamos
      ```css
      header {
        color: red;
      }
      ```
    * Selector de id: el selector id nos ayuda a seleccionar una etiqueta que contenga el atributo id y sea igual al contenido de este.
      ```css
      #selectorId {
        color: red;
      }
      ```
    * Selector de clase: el selector clase nos ayuda a poder seleccionar multiples elementos que tengan el atributo class y sea igual al contenido de este.
      ```css
      .botones {
        background-color: red;
      }
      ```
    * Selector de atributo: este selector nos ayuda a poder seleccionar un input especifico.
      ```css
      input[type="text"] {
        color: red;
      }
      ```
2. Selectores Compuestos
    * Selector de herencia: este selector nos ayuda a poder seleccionar todos los elementos que son hijos del padre.
      ```css
      ul li {
        color: red;
      }
      ```
    * Selector de hijo: nos ayuda a seleccionar todos los hijos directos.
      ```css
      ul li > a {
        color: red;
      }
      ```
    * Selector de hermano siguiente: nos ayuda a seleccionar el hijo que sigue.
      ```css
      header + section {
        color: red;
      }
      ```
    * Selector de hermano general: este selector nos ayuda a elegir todos los hermanos que son hermanos de una etiqueta.
      ```css
      header ~ h2 {
        color: red;
      }
      ```
# Box Model
En el ```box_model.html``` se podra ver los conceptos y ejemplos
1. ¿Que es box model?
2. Uso particular de selector universal.
3. Explicando las capas del box model.
    * Capa interna
    * Capa externa
4. Explicando el shorthand padding y margin.
    * Padding
    * Margin
5. Colapso de margenes verticales
6. Centrado perfecto horizontal
  <img src="https://github.com/RFMC22/RFMC22/assets/60860968/6cb8b338-ce55-40fa-8ab4-d2a178b3e4f4">