**Title**
----
  API (Application Programming Interface) 

* **Descripción**

Es un intermediario de software que permite que dos aplicaciones se comuniquen entre si. Interpreta datos y le presenta la información que desea de manera legible.  Esta tiene su propio ciclo de vida de desarrollo de software (SDLC) de diseño, prueba, construcción, administración y control de versiones. Además, las API modernas están bien documentadas para consumo y versiones; se adhieren a los estándares (generalmente HTTP y REST), las cuales le permite al desarrollador fácil acceso.

* **URL**

  Su url normalmente se acompaña con endpoinst los cuales pueden tener métodos como:

* **Methodos:**
  

  `GET` | `POST` | `DELETE` | `PUT`
  
*  **URL Params**

   Y agregarse parametros para la consulta y el filtrado

   **Required:**
 
   `id=[integer]`


* **Success Response:**
  
  Adicionalmente cada petición regresa una respuesta como:

  * **Code:** 200 <br />
    **Content:** `{ id : 12 }`
 
* **Error Response:**

  ó un mensaje de error si es el caso:

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : "Log in" }`

  OR

  * **Code:** 422 UNPROCESSABLE ENTRY <br />
    **Content:** `{ error : "Email Invalid" }`
