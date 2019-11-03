# upaded
Repositorio UPADED

Este es el repositorio de UPADED

#Correr el servidor localmente
`bundle exec jekyll serve`

#Uso de tablas
El template utiliza bootstrap por lo que cualquier clase de boostrap funciona. En este caso para tablas.
https://getbootstrap.com/docs/4.3/content/tables/

#Hacer cambios en el css
Nota: En verdad no veo mucho caso modificar el css ya que el template usa bootstrap y bootstrap trae muuuuchas clases que se pueden aplicar directamente, por ejemplo para los espacios
https://getbootstrap.com/docs/4.3/utilities/spacing/

Pero si aun se necesita modificar entonces:

Puedes modificar `/assets/scss/style.scss`
Agregar las clases ahi.

Abrir otro CMD de Bash. Ir a la carpeta del proyecto
Ejecuta `gulp`

Tarda como 1 minuto y de ahi podras ver los cambios

Importante: Asegurarse de terminar la tarea de gulp con ctrl + C. De lo contrario los cambios a Jekyll no se reflejan!!



