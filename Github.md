# **Introducción a Github**
### **Raimundo Linares Quevedo**
**GitHub** es una plataforma web que permite alojar y gestionar repositorios de código utilizando el sistema de control de versiones **Git**. Un 
sistema de control de versiones registra el historial de cambios de un proyecto, de forma que es posible consultar versiones anteriores, 
comparar modificaciones y recuperar el estado del código en cualquier momento del desarrollo.

# **Pasos a seguir**
 1. Crear una cuenta en **GitHub**
    
    >1- Acceder a la página web github.com.
    2- Pulsar en el botón ["Sign up"](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) (Registrarse).
    3- Introducir un correo electrónico, una contraseña y un nombre de usuario.
    4- Verificar la cuenta a través del correo electrónico de confirmación.
   >
##### _Una vez completado el registro, el usuario dispone de un perfil propio desde el que puede crear y gestionar repositorios._
 2. Crear un repositorio
 
    >1- Desde la página principal de GitHub, pulsar en el botón **"New"** (Nuevo) o en el icono **"+"** situado en la esquina superior derecha.
    2- Asignar un nombre al repositorio.
    3- Elegir si el repositorio será público (visible para cualquier usuario) o privado (solo accesible para los colaboradores autorizados).
    4- Opcionalmente, añadir un archivo README, un archivo .gitignore y una licencia.
    5- Pulsar en "Create repository" para finalizar.
>
3. Realizar un commit
**_Un commit es una "fotografía" de los cambios realizados en el proyecto en un momento determinado, acompañada de un mensaje descriptivo. Los commits son la base del historial de versiones._**

    >1- Modificar o añadir archivos dentro de la carpeta del proyecto.
    2- Añadir los archivos modificados al área de preparación (staging area): git add nombre-del-archivo
    #o para añadir todos los cambios:
    git add
    >
    1. Confirmar los cambios mediante un commit, incluyendo un mensaje que describa lo realizado:
    >git commit -m "Descripción breve de los cambios realizados"
>
**_Es recomendable hacer commits pequeños y frecuentes, con mensajes claros, para facilitar el seguimiento del historial del proyecto._**
4. Realizar un push
**_El comando push envía los commits realizados en el repositorio local al repositorio remoto alojado en GitHub, de forma que los cambios quedan disponibles en la nube y accesibles para el resto de colaboradores._**
    1. Ejecutar el siguiente comando desde la carpeta del proyecto:
    >git push origin main
    >
    1. Si es la primera vez que se realiza un push, es posible que GitHub solicite autenticación mediante usuario y contraseña, o mediante un token de acceso personal.
    
**_Tras el push, los cambios pueden consultarse directamente en la página del repositorio en GitHub._**
# Conclusiones
GitHub facilita el trabajo con control de versiones al ofrecer una interfaz sencilla sobre Git, así como herramientas adicionales de colaboración. El flujo básico de trabajo (crear repositorio, clonar, modificar, hacer commit y hacer push) constituye la base sobre la que se apoyan flujos más avanzados, como el uso de ramas o las pull requests.
El uso correcto de mensajes de commit descriptivos y la realización de subidas frecuentes ayudan a mantener un historial de proyecto claro y facilitan la colaboración entre distintos desarrolladores.

## Bibliografía
    • Documentación oficial de GitHub: https://docs.github.com
    • Documentación oficial de Git: https://git-scm.com/doc
