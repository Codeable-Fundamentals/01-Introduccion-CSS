Una pseudo-clase es una clase que aplica automáticamente el navegador cuando un elemento HTML se encuentra en un estado específico o cumple una condición en particular. El ejemplo más común es la pseudo-clase :hover que se aplica automáticamente cuando el mouse pasa por encima del elemento.

https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes


Aqui una lista de los mas comunes:
| Pseudo-clase       | Descripción breve |
|--------------------|-------------------|
| `:hover`           | Aplica estilos cuando el usuario pasa el cursor sobre un elemento. |
| `:active`          | Se activa mientras se está haciendo clic en el elemento. |
| `:focus`           | Aplica estilos cuando el elemento tiene el foco (como un campo de texto activo). |
| `:visited`         | Estiliza enlaces que ya han sido visitados. |
| `:link`            | Estiliza enlaces que **no** han sido visitados. |
| `:first-child`     | Selecciona el primer hijo de su padre. |
| `:last-child`      | Selecciona el último hijo de su padre. |
| `:nth-child(n)`    | Selecciona el hijo n-ésimo de su padre (por ejemplo, `:nth-child(2)`). |
| `:nth-of-type(n)`  | Similar a `:nth-child`, pero solo cuenta los elementos del mismo tipo. |
| `:not(selector)`   | Selecciona todos los elementos que **no** coinciden con el selector dado. |
| `:checked`         | Selecciona inputs (`radio`, `checkbox`) que están marcados. |
| `:disabled`        | Selecciona elementos deshabilitados (como botones o campos de formulario). |
| `:enabled`         | Selecciona elementos habilitados. |
| `:required`        | Selecciona campos de formulario que son obligatorios. |
| `:valid` / `:invalid` | Aplica estilos a campos de formulario según si son válidos o no. |