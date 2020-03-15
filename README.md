# AREP-AWS PATRONES ARQUITECTURALES S3, EC2 Y RDS

En este tutorial podrá aprender como se crea y como se despliega:
- Un contenido estatico en S3.
- Una aplicación desarrollada en Maven y conectada a una base de datos RDS postgresql.
- Una base de datos en eRDS con postgresql.

## PATRONES ARQUITECTURALES
Una empresa lo ha contratado para capacitar a sus ingenieros en la construcción de sitios web dinámicos sobre Amazon Web Services. Para esto usted decidió construir un tutorial y un video que permita a los ingenieros hacer lo siguiente:

1. DESPLEGAR UN SITIO ESTÁTICO USANDO S3.

      1.1 Entramos a la consola de AWS y en la parte de servicios escribimos S3.
      
      ![Captura](https://user-images.githubusercontent.com/48154086/76712696-20af6480-66e9-11ea-92f5-f0928b6a2b87.PNG)
      
      1.2 Una vez ubicados en el servicio S3 crearemos un nuevo bucket 
      
      ![Captura1](https://user-images.githubusercontent.com/48154086/76712698-2147fb00-66e9-11ea-8209-84079c912dad.PNG)
      
      1.3 El bucket lo llamaremos "staticbucketresource". 
      
      ![Captura2](https://user-images.githubusercontent.com/48154086/76712699-21e09180-66e9-11ea-9191-5f5b62537fea.PNG)
      
      1.4 Damos click a las opciones de siguiente hasta crear un nuevo bucket. 
      
      ![Captura3](https://user-images.githubusercontent.com/48154086/76712700-22792800-66e9-11ea-95f4-8198625a9f35.PNG)
      ![Captura4](https://user-images.githubusercontent.com/48154086/76712702-2311be80-66e9-11ea-89a9-64c35a256efd.PNG)
      ![Captura5](https://user-images.githubusercontent.com/48154086/76712704-260caf00-66e9-11ea-8de1-bb77eff54593.PNG)
      
      1.5 Editamos la configuración de acceso público, para ello seleccionaremos la opción que se tiene en pantalla. 
      
      ![Captura6](https://user-images.githubusercontent.com/48154086/76712705-26a54580-66e9-11ea-92ed-97bef7556cab.PNG)
      
      1.6 Una vez hecho esto vamos a quitar el bloqueo de acceso público y guardar.  
      
      ![Captura7](https://user-images.githubusercontent.com/48154086/76712707-273ddc00-66e9-11ea-9547-419a684db23e.PNG)
      
      1.7 Para terminar la configuración de acceso escribimos la palabra "confirm" en la pantalla que nos ha salido justo despues de guardar las configuraciones.
      
      ![Captura8](https://user-images.githubusercontent.com/48154086/76712708-27d67280-66e9-11ea-8b5b-67bd15423bc6.PNG)
      
      1.8 Entramos al bucket creado y señalamos la opción de subir archivo. 
      
      ![Captura9](https://user-images.githubusercontent.com/48154086/76712724-39b81580-66e9-11ea-82b8-565c0e2eeeea.PNG)
      
      ![Captura10](https://user-images.githubusercontent.com/48154086/76712714-302ead80-66e9-11ea-8285-0b1179695a9c.PNG)
      
      1.9 Aparecerá una pantalla como la siguiente y subiremos el archivo que deseamos. 
      
      ![Captura11](https://user-images.githubusercontent.com/48154086/76712716-345acb00-66e9-11ea-99a2-78f32db87b06.PNG)
      
      1.10 En mi caso subí una imagen de tipo jpg de un paisaje de Bogotá.
      
      ![Captura12](https://user-images.githubusercontent.com/48154086/76712717-36248e80-66e9-11ea-9465-921da18f24e5.PNG)
      
      1.11 Aparecerá la imagen como subida exitosamente y damos click en ella para entrar. 
    
      ![Captura13](https://user-images.githubusercontent.com/48154086/76712718-36bd2500-66e9-11ea-8a7a-bbd84640b117.PNG)
      
      1.12 Damos click en la URL del objeto. 
     
      ![Captura14](https://user-images.githubusercontent.com/48154086/76712720-3755bb80-66e9-11ea-8b6b-cfaa90971336.PNG)
      
      1.13 En la siguiente pantalla podemos ver la url del objeto y la imagen que se subió. 
     
      ![Captura15](https://user-images.githubusercontent.com/48154086/76712721-37ee5200-66e9-11ea-8323-dab4c5b214fe.PNG)
      
      

      
      
      
      



## Autor 

Sarah Camila Vieda Castro



## Despliegue
[![CircleCI](https://circleci.com/gh/camilavieda04/Patrones-Arquitecturales-Lab6-Arep.svg?style=svg)](https://circleci.com/gh/camilavieda04/Patrones-Arquitecturales-Lab6-Arep)



## Licencia 

This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details.
