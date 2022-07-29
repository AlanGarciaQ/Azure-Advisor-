# Azure Advisor 
**Objetivo:** Conocer el funcionamiento del recurso de Azure Advisor.   

![](/imagenes/advisor_.png)

**Requisitos**
- Cuenta de Azure con una suscripción activa
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs.  

**Pasos**  
Se inicia sesión en Portal.Azure.com  
En la barra de búsqueda escribimos “Asesor” y lo seleccionamos.  
En el menú de la parte de la izquierda le damos clic en la opción de Alertas.  
Seleccionamos Nueva alerta de advisor.  
![Imagen 1](/imagenes/Imagen1.png)

En la ventana que se abrió llenamos lo siguiente:  

**En Detalles del proyecto**  
Suscripción: La suscripción que queramos utilizar.  
Grupo de recursos: Seleccionamos uno que hayamos creado con anterioridad.

**En Condición**  
Configurado por: Seleccionamos Categoría y nivel de impacto.  
Categoría: Seleccionamos costo.  
Nivel de impacto: Seleccionamos baja.  
![](/imagenes/Imagen2.png)

**En Grupo de acciones**  
Nombre del grupo de acciones: Seleccionamos uno existente o creamos uno nuevo.

**En Detalles de alertas**  
Nombre de la regla de alertas: Escribimos el que queramos.  
Descripción: Escribimos la descripción de la alerta que vamos a crear.  
Habilitar regla tras la creación: Seleccionamos sí.

Para terminar, damos clic en el botón de revisar y crear, y luego en crear.  
![](/imagenes/Imagen3.png)

Con esto configuramos una alerta para que Advisor nos informe sobre posibles mejoras o cambios que podamos realizar.