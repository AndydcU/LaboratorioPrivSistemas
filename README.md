# Actividad: LaboratorioPrivSistemas

## Objetivo:  Estudiante 8: Subir un archivo de configuración personalizada a /etc/ desde el navegador Webmin.

Documentacion:

## Pasos realizados
1. En el dashboard de Webmin me logue utilizando mis credenciales Estudiante08 y la contrase;a Seminario2025.
2. Se tiene que eliminar en mi caso el numero 443 para poder acceder al dashboard. ![image](https://github.com/user-attachments/assets/d3048037-ffdc-4e79-ba16-08b21258203e)
3. Luego busque el apartado File manager dentro de las herramientas de Webmin.  ![image](https://github.com/user-attachments/assets/f00aece8-c2a6-474e-99d6-78e16bcae212)
4. Accedi a la carpeta y ya estoy listo para subir archivos,  ahora bien el siguiente paso es investigar que tipo de archivos puedo subir aca, en el siguiente paso explicare
   que archivos coloque y el porque. ![image](https://github.com/user-attachments/assets/db038303-02c0-4a54-aad5-ab4fbd871a90).
5. Empezamos sabiendo que en la carpeta /etc/ de webmin se encuentran todas las configuraciones del sistema.  Por ejemplo creare:
    - mi_config.conf ->  este archivo nos sirve para cualquier servicio o script personalizado que nosotros mismos agreguemos, por motivos de seguridad y no botar
      el servidor solo lo crearemos. ![image](https://github.com/user-attachments/assets/9021bc47-db0e-49eb-8cdd-859cf5bcaea3)
    - mis_tareas  en la carpeta cron.d  ->  aqui se pueden colocar tareas programadas ![image](https://github.com/user-attachments/assets/9929453b-9fae-46ae-92da-fe3070744b0a).
    - Por ejemplo un archivo critico es ssh server, cualquier modificacion aqui puede botar el servidor facilmente.



## Resultados
- Investigue y comprendi para que sirve la carpeta /etc/
- logre colocar un archivo de mi_config.conf cumpliendo con la tarea asignada.


## Capturas de pantalla
- Adjunte capturas de pantalla para que pueda visualizar de forma correcta mi trabajo. 

