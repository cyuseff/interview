# Scenario

Estamos trabajando en el flujo de creación de usuarios y el
desarrollador encargado está de vacaciones!

Esta es un pasó critico de nuestra plataformas y lo necesitamos
ahora ASAP!!!

Sigue los requerimientos e instrucciones para completar la tarea asignada.

# Requirements
## Profile Form
1. Valida que el formulario esteé enviando los siguientes datos:
  * Email
  * Password
  * Gender
  * City
  * Un hidden field con el nombre 'referal' y el valor de 'profile_page'
2. Asegurate que todos los field tengan un label y sigan la misma esrtuctura.
3. Todos los fields son requeridos
4. Valida que los fields de passwords sean identicos antes de enviar el formulario.

5. Rellena el campo de ciudades
  * Usa la función `initForm` para crear las opciones de ciudades.
  * `cities` simula una respuesta de un API, limpia los resultados antes de crear las opciones.
6. Postea el formulario a success.html usando el método GET

## Extra Points
* Aplica un basic styling al formulario para mejorar como se ve.