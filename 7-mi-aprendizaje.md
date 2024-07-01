# COMPLETAR  

Después de completar la práctica y la tarea, he adquirido una comprensión más profunda de Docker y sus aplicaciones. Aquí están mis principales aprendizajes:

Limitar recursos: Aprendí cómo limitar los recursos de un contenedor Docker, lo que es crucial para garantizar que un contenedor no consuma todos los recursos del sistema.
Manejo de la memoria: Aprendí cómo Docker maneja la memoria y cómo puedo ajustar la configuración de la memoria para optimizar el rendimiento del contenedor.
Procesador: Aprendí cómo Docker utiliza el procesador y cómo puedo asignar núcleos de CPU específicos a un contenedor.
Healthcheck: Aprendí cómo implementar verificaciones de salud en un contenedor Docker para asegurarme de que está funcionando correctamente.
Dockerfile: Aprendí cómo crear un Dockerfile, que es un archivo de texto que Docker lee para construir una imagen. Esto me permitió personalizar mis imágenes de Docker.
Políticas de reinicio: Aprendí sobre las diferentes políticas de reinicio disponibles en Docker y cómo pueden ayudar a garantizar que mis contenedores se recuperen automáticamente de los fallos.
Durante la práctica, me encontré con un problema al intentar limitar los recursos de un contenedor. Inicialmente, no estaba seguro de cómo hacerlo, pero después de investigar y experimentar, descubrí que podía usar la opción -m en el comando docker run para limitar la memoria de un contenedor. Este fue un aprendizaje valioso para mí, ya que ahora sé cómo controlar el uso de recursos de un contenedor.

Y en el ejercicio del dockerfile era necesario usar el atributo -y en los comandos RUN para que CentOS entienda que debe ejecutar esos comandos sin esperar interaccion.
