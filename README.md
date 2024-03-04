# ROKS-NextJS-React-Framework
Para el desarrollo de esta guia de despliegue, se tiene como base el desarrollo de una aplicación basada en la librería NextJS de javascript y su posterior despliegue en un Cluster de OpenShift que se encuentra alojado en IBM Cloud.
<br/>
## Indice 
<br/>

## Pre-requisitos
<br/>
Para que la aplicación se despliegue en el cluster de OpenShift, se necesita de un archivo de configuración, siendo compatibles dockerfile, yaml y devfile. Un ejemplo de archivo dockerfile para NextJS se encuentra en el siguiente repositorio: https://github.com/davidravelo1/Pokemon-Ecommerce-.git.

## Despliegue la consola web de OpenShift desde IBM Cloud  

1. Asegurese de encontrarse en la cuenta en la cual va a desplegar la aplicación, posteriormente, ingrese a **Resource list** y posteriormente a **Containers**, debe tener **activa** la instancia de openshift.

<div align="center"><img width="800" src="Img/IBM cloud.png"></div>
<br/>

2. Ingrese a la instancia de openshift y de click en **OpenShift web console**.

<div align="center"><img width="800" src="Img/ibmcloud2.png"></div>

## Despliegue aplicación de NextJs en OpenShift

<br/>

1. Dentro de la instancia, cambie de administrador a developer. Posteriormente, en proyect, cree un nuevo proyecto.

<div align="center"><img width="800" src="Img/Create-Proyect.jpg"></div>

42 En el proyecto creado, ingrese a la pestaña +Add y seleccione la opción de importar desde repositorio de GitHub.

<div align="center"><img width="800" src="Img/Add-Proyect.jpg"></div>


3. Ingrese el link del repositorio de la aplicación en GitHub.


<div align="center"><img width="800" src="Img/Import-from-GitHub.jpg"></div>

4. Seleccione la opción de editar la estrategia de importación


<div align="center"><img width="800" src="Img/Edit-Import.jpg"></div>



