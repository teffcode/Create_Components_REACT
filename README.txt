📦  DESARROLLO ORIENTADO A COMPONENTES 📦 

- Pensar que la aplicación es un conjunto de COMPONENTES 
  Esto tiene que ver con la SEPARACIÓN DE RESPONSABILIDADES

  Por ejemplo:

  🔺  BACKEND -> MVC (Datos, Interfaz y Lógica)
  🔺  FRONTEND -> TEL (Templates, Estilos y Lógica -> HTML, CSS y JS)

  Lo cuál no tiene mucho sentido porque no se están separando
  las responsabilidades como tal sino los archivos.

  Es por esto que se crearon los COMPONENTES !

  ✏️  ¿ Qué es un componente ?

  - Es CADA parte pequeña de nuestra aplicación
    y se pueden combinar para hacer apliciones más grandes

  ✏   ¿ Cómo se crea un componente ?

  - Con HTML, CSS y JS 

  ✏️   ... y, ¿ Los componentes en REACT ?

  - TODO ES JAVASCRIPT
  - Ya no se tiene el HTML, CSS y JS por separado
    sino que ahora se tiene TODO JUNTO !


👩🏻‍💻   FORMAS DE CREAR UN COMPONENTE  👩🏻‍💻

   💛  FUNCIÓN PURA:

      - No depende de los datos externos, solo de los props
      - Forma más fácil

   💛  CLASES

      - Clase que hereda (extends) de React.component
      - Se tiene acceso a más funcionalidades de React
      - Método obligatorio: render() 
