# Spartacus Fitness Center

## Contenido
<details>
  <summary>Tabla contenido</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#organigrama">Organigrama</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#historias-de-usuario">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
        <li><a href="#plan-de-iteraciones">Plan de itraciones</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#casos-de-uso">Casos de uso</a></li>
        <li><a href="#diagrama-de-casos-de-uso">Diagrama de casos de uso</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
        <li><a href="#diagrama-de-actividadess">Diagrama de Actividades</a></li>
        <li><a href="#modelo-arquitectura-mvc">Modelo Arquitectura MVC</a></li>
        <li><a href="#modelo-BD">Modelo BD</a></li>
        <li><a href="#estandar-de-programación-camel-case">Estándar de programación Camel Case</a></li>
      </ul>
    </li>          
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
      </ul>
    </li>
    <li>
      <a href="#proceso-de-instalación">Proceso de instalación</a>
      <ul>
        <li><a href="#instalación-de-spring-tool-suit-4">Instalación de Spring tool suit 4</a></li>
        <li><a href="#clonar-el-proyecto">Clonar el proyecto</a></li>
        <li><a href="#proceso-de-instalación-para-el-front-end">Proceso de instalación para el Front-end</a></li>
        <li><a href="#proceso-de-instalación-para-el-back-end">Proceso de instalación para el Back-end</a></li>
      </ul>
    </li>
    <li>
      <a href="#guía">Guía</a>
      <ul>
        <li><a href="#manual-de-usuario">Manual de usuario</a></li>
      </ul>
    </li> 
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
#### Acerca del proyecto
Nombre del proyecto 
* iTTiVA Project

Requisitos.
* Internet 
* Equipo de cómputo
* Tener instalado Angular v14.2.5
* Tener instalado Node JS v16.14.2
* Tener instalado Visual Studio Code 
* Tener instalado Spring boot suite 4

<!-- Descripción -->
## Descripción.
La gestión de usuario y gestión de privilegios resulta una parte fundamental para garantizar la seguridad y la eficiencia de nuestro sistema. Su función principal se centra en el proceso de inicio de sesión, el cual está diseñado para mostrar vistas específicas a cada usuario dependiendo de sus permisos. De esta manera, se puede controlar de manera efectiva el acceso y las acciones que pueden realizar los usuarios en nuestro sistema.
La idea principal detrás de este proceso de inicio de sesión es garantizar que cada usuario tenga acceso solo a la información y herramientas que le corresponden según su rol en el sistema. Por ejemplo, si un usuario tiene el rol de administrador, se le mostrarán vistas adicionales que le permitirán realizar tareas de administración, mientras que un usuario con un rol limitado solo tendrá acceso a las vistas y herramientas necesarias para su trabajo diario.
Este sistema de gestión de usuarios y privilegios nos permite mantener el sistema organizado y estructurado de manera eficiente, al mismo tiempo que asegura la integridad de los datos y la privacidad de los usuarios. Además, ayuda a prevenir errores y malas prácticas, ya que los usuarios no podrán realizar acciones que no les corresponden según su rol determinado. En resumen, esta función es esencial para garantizar la seguridad y el éxito de nuestro sistema.
La implementación de nuestro modulo tomo dos meses y medio en completarse, esto incluye el diseño de la arquitectura de seguridad del sistema, la creación de componentes de interfaz de usuario, la implementación de servicios para la gestión de permisos y la integración con el backend del sistema.

Objetivos Generales:
* Mejorar la eficiencia: Un software de gestión de gimnasios puede ayudar a automatizar los procesos de administración y gestión de los clientes, lo que puede mejorar la eficiencia del gimnasio en general. Por ejemplo, se pueden automatizar tareas como el seguimiento de los pagos de los clientes, la gestión de las membresías, el seguimiento de la asistencia y el acceso a las instalaciones.

* Aumentar la satisfacción del cliente: Puede mejorar la experiencia del cliente al proporcionar acceso a información en línea y permitir la gestión en línea de su membresía. Los clientes pueden realizar reservas, cancelaciones, verificar su asistencia y ver sus progresos en línea.

* Optimizar la gestión de la información: El software de gestión de gimnasios puede ayudar a organizar y administrar toda la información importante del gimnasio, como los datos de los clientes, los registros de asistencia y los horarios de las clases. Esto puede ser muy útil para tomar decisiones informadas y mejorar el funcionamiento del gimnasio.

* Aumentar la seguridad: La gestión de usuarios y privilegios puede mejorar la seguridad del gimnasio al garantizar que solo las personas autorizadas tengan acceso a las instalaciones y los datos confidenciales. Además, la gestión de usuarios y privilegios puede ayudar a evitar el uso indebido o el abuso de los recursos del gimnasio.

*	Facilitar la toma de decisiones: El software de gestión de gimnasios puede proporcionar datos y análisis importantes que pueden ser utilizados para tomar decisiones informadas y mejorar la eficiencia del gimnasio. Por ejemplo, se puede obtener información sobre las horas pico y las horas bajas, la cantidad de clientes en promedio por día y el rendimiento financiero del gimnasio.



#### Gestion de Usuario
Objetivos:
* Control de acceso: Garantizar que solo las personas autorizadas tengan acceso a las instalaciones y a la información confidencial del gimnasio. Para ello, se pueden establecer diferentes niveles de acceso y permisos para los usuarios, según sus roles y responsabilidades.

*	Gestión de membresías: Ayudar a gestionar las membresías de los clientes, lo que incluye el seguimiento de pagos, la renovación de membresías, el registro de nuevos clientes y la actualización de la información personal de los clientes.

*	Gestión de reservas: Permitir a los clientes realizar reservas en línea, lo que puede mejorar la experiencia del cliente y optimizar la utilización de las instalaciones del gimnasio.

*	Seguimiento de asistencia: Permitir llevar un registro de la asistencia de los clientes, lo que puede ser utilizado para el seguimiento del progreso de los clientes y para la planificación de las actividades del gimnasio.

*	Comunicación con los clientes: Permitir la comunicación personalizada con los clientes, lo que puede mejorar la relación entre el gimnasio y sus clientes y aumentar la satisfacción del cliente. Por ejemplo, se pueden enviar recordatorios de pagos, notificaciones sobre horarios de clases y promociones especiales a través del software de gestión de usuarios.



Características:
* Utiliza un sistema de asignación de roles al usuario, el rol trae con los diferentes privilegios
dependiendo el rol.
* Permite la realización de diferentes actividades dependiendo del rol.

Funcionalidades:
* Creación, actualización, eliminación y búsqueda de un determinado usuario.
* Asignación de los diferentes roles.
* Creación de nuevos roles con diferentes privilegios.

#### Gestión de Privilegios
Objetivos:
•	Control de acceso: Garantizar que solo los usuarios autorizados tengan acceso a los recursos del sistema y a la información confidencial. 
•	Seguridad del sistema: Proteger el sistema de posibles amenazas, como virus o intentos de acceso no autorizado. Al restringir el acceso solo a usuarios autorizados, se puede reducir el riesgo de exposición de información confidencial y mejorar la seguridad del sistema en general.
•	Cumplimiento normativo: Ayudar a garantizar que se cumplan los requisitos legales y normativos en materia de privacidad y seguridad de la información. Por ejemplo, algunos reglamentos pueden requerir que se mantengan registros detallados de quién ha accedido a la información confidencial y cuándo.
•	Mejora de la eficiencia: La gestión de privilegios del usuario puede ayudar a mejorar la eficiencia del sistema al permitir que cada usuario tenga acceso solo a los recursos y la información necesarios para realizar su trabajo. Esto puede reducir el riesgo de errores y mal uso de los recursos del sistema, y mejorar la productividad de los usuarios.
•	Auditoría y seguimiento: La gestión de privilegios del usuario puede permitir llevar un registro detallado de quién ha accedido a qué información y cuándo, lo que puede ser útil para fines de auditoría y seguimiento. Esto puede ayudar a identificar posibles problemas de seguridad o abuso de los recursos del sistema y tomar medidas preventivas adecuadas.

Características:
* Permite la definición de roles y permisos personalizados para cada empleado.
* Permite la asignación de permisos y accesos al sistema.
* Facilita el monitoreo del acceso a información confidencial del gimnasio.
* Garantiza la seguridad de la información mediante la restricción de accesos.

Funcionalidades:
* Definición y gestión de roles y permisos personalizados para cada empleado.
* Asignación de permisos y accesos al sistema.
* Monitoreo del acceso a información confidencial del gimnasio.
* Restricción de accesos a información confidencial para garantizar la seguridad de la información.

## Organigrama.
![image](https://user-images.githubusercontent.com/106614143/232810415-978b05e4-6990-4909-b8ea-27257fb7c7fc.png)

## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

## Historias de Usuario
#### Historia de usuario Gestión de Usuario.
El usuario administrador ingresara al sistema a través de su usuario y contraseña ingresando al módulo de Usuarios
en donde tendrá tres opciones: agregar usuario, actualizar usuario y eliminar usuario, estas opciones permiten que el
administrador asigne, actualice y elimine los usuarios del gimnasio.

![image](https://user-images.githubusercontent.com/123588637/232643589-6f34b8c1-a5cb-4f3a-919d-84f42073308f.png)

#### Historia de usuario Gestión de Privilegios.
El usuario administrador ingresara al sistema a través de su usuario y contraseña ingresando al módulo de Usuarios
en donde tendrá las opciones de asignarle un rol a determinado empleado o usuario permiten que el administrador
asigne, actualice y elimine los roles por lo tanto los privilegios del gimnasio.

#### Diagrama de clases
![image](https://user-images.githubusercontent.com/123588637/232643662-1f8e82a9-01b6-44ab-819b-08bef73cd8b7.png)

## Plan de iteraciones

![image](https://user-images.githubusercontent.com/106614143/232811275-03c7dcb2-70fa-4953-b74a-b87b22ea77e6.png)

#### Requisitos por sprint

![image](https://user-images.githubusercontent.com/106614143/232849496-e3494f68-a046-42fd-921b-f20c5fc9f39d.png)

#### Diseño de la Solución
En ésta sección se indicará los artefactos generados en base a la solución.


![Imagen de WhatsApp 2023-04-18 a las 20 47 27](https://user-images.githubusercontent.com/123511310/232954024-1caba595-52ba-4610-8507-999684c96c9e.jpg)

#### Casos de Uso


![image](https://user-images.githubusercontent.com/123588637/232643422-884202a4-ca0f-4d0c-9006-d74da3506bf6.png)
![image](https://user-images.githubusercontent.com/123588637/232643460-c6e6da54-cad2-462d-88f3-56ae9ed3920a.png)
![image](https://user-images.githubusercontent.com/123588637/232643486-806862c0-8985-4f84-aea1-ae44906cab29.png)
![image](https://user-images.githubusercontent.com/123588637/232643515-b0234f0c-41da-4cb7-ab19-ffda99548342.png)

#### Diagrama de casos de uso

![image](https://user-images.githubusercontent.com/123588637/232643366-795855d4-9359-44bd-aa17-5961fb64125c.png)

## Diagrama de actividades
#### Administrador: Eliminar empleado

El administrador ingresará a la página, donde posteriormente iniciará sesión, si el sistema verifica que los datos ingresados son correctos, será redirigido a la pantalla principal. Luego podrá seleccionar al empleado que desea eliminar y en seguida, el sistema arrojará un mensaje de confirmación donde el administrador decidirá si en verdad desea eliminarlo o no.

En caso de que el administrador decida que no desea eliminarlo, el sistema redireccionará al apartado de empleados.

![image](https://user-images.githubusercontent.com/123588637/232643724-29d8fa10-e6bc-4fbe-aad5-e56c82253c9f.png)

#### Administrador: Editar empleado

El administrador ingresará a la página, donde posteriormente iniciará sesión, si el sistema verifica que los datos ingresados son correctos, será redirigido a la pantalla principal. Luego podrá seleccionar al empleado que desea modificar y en seguida, el sistema redireccionará a un formulario con los datos originales para que puedan ser modificados, luego, al dar click en aceptar, el sistema arrojará un mensaje de confirmación donde el administrador decidirá si en verdad desea editarlo o no.

En caso de que el administrador decida que no desea modificarlo, el sistema redireccionará al apartado de empleados.

![image](https://user-images.githubusercontent.com/123588637/232644002-8d9ab609-d1ef-459a-9d16-aec70635aee6.png)

#### Administrador: Crear empleado

El administrador ingresará a la página, donde posteriormente iniciará sesión, si el sistema verifica que los datos ingresados son correctos, será redirigido a la pantalla principal. Luego podrá acceder al apartado de añadir empleados; en esta pantalla se mostrará un formulario para que puedan ser añadidos los datos del empleado, si estos datos son correctos, el sistema agregará al empleado a la base de datos, en caso contrario, si los datos son incorrectos se mandará un mensaje de error.

![image](https://user-images.githubusercontent.com/123588637/232644059-8c8482fb-17d8-4375-b3b0-955637433a5f.png)


<!-- Modelo Arquitectura MVC -->
## Modelo Arquitectura MVC

1. El usuario envía una petición al Controlador via una url.
2. El Controlador solita al modelo los datos.
3. El modelo devuelve los datos.
4. El controlador selecciona una vista.
5. Se devuelve la vista seleccionada al controlador
6. El controlador devuelve una vista (Sistema gymnasio) que carga los datos del modelo seleccionado.

#### Modelo MVC 
![ModeloMVC](https://user-images.githubusercontent.com/123511310/232953820-4601b0bf-566a-43fe-a960-4ed003550e7a.png)

#### Diagrama de Componentes.
![image](https://user-images.githubusercontent.com/123511310/232948963-1e0f7a9e-9362-4b79-886b-92e487cea31d.png)

<!-- Modelo BD -->
## Modelo BD

![image](https://user-images.githubusercontent.com/106614143/232937304-d4b68b57-e51e-4b5d-a1c8-e4dd89d8b754.png)

Tipos de datos:
* id: Number
* username: String
* photo: String
* age: Number
* turn: String
* email: String
* phone: String
* password: String
* role: Array

## Estándar de base de datos

* Nombre de la colección en singular.
* Nombre de los campos de cada colección sin incluir mayúsculas.
* Nombre de la colección iniciando con mayúscula.
* Se incluyen términos en ingles adecuados a la base de datos usada.
* Si se incluye un dato tipo cadena, se usan comillas.

## Estándar de programación Camel Case

Cuando un nombre del campo de la colección está constituido por dos palabras, se combinan estas palabras sin usar ningún carácter especial.
Comentarios incluidos al inicio con su nombre de clase respectivamente por cada uno.
Los nombres de las variables deben ser claros para saber el uso de cada una.
En los métodos se hace el uso de minúsculas únicamente.
Nombres de constantes en mayúsculas.


<!-- Objetivos -->
#### Objetivos
El proyecto consiste en el rediseño de la página oficial de la empresa Optimen S.A de C.V. para incluir nuevas funcionalidades que brinden información actualizada sobre la empresa y sus avances en TI. Se busca lograr un sitio web altamente eficiente, con una rápida velocidad de carga para una navegación óptima. El administrador root podrá controlar los permisos de acceso de los usuarios, mientras que los creadores de contenido podrán crear, editar, eliminar y consultar noticias y eventos. Además, las noticias y eventos se mostrarán en la página principal para mantener a los usuarios visitantes informados acerca de las últimas novedades de la empresa.


<!-- Análisis del proyecto -->


<!-- Pruebas proyecto -->
## Pruebas
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Casos de prueba -->
### Casos de prueba

#### Iniciar sesión exitosamente
![image](https://user-images.githubusercontent.com/106614143/232855113-c7a29cf9-9b28-4fe6-917d-7e2f99a8cb69.png)

#### Iniciar sesión erroneamente

![image](https://user-images.githubusercontent.com/106614143/232855178-342d1085-3305-44ab-9290-9113d428ac7f.png)


#### Añadir empleado

![image](https://user-images.githubusercontent.com/106614143/232855243-0b7ca1cd-8863-4084-9cd7-78b08507016e.png)

#### Cerrar sesión

![image](https://user-images.githubusercontent.com/106614143/232855302-dfa574fd-d42c-4e09-999f-379568d72239.png)

<!-- Instalación -->
# Proceso de instalación

## Instalación de Spring tool suit 4

1. Ingresaremos al link: https://spring.io/tools, e iremos a la sección "Spring Tools 4 for Eclipse", dando clic en el botón de descarga para Windows(en este caso).

![image](https://user-images.githubusercontent.com/106614143/232860987-d35f0c2e-b4c6-4001-a57f-d265b7aa9c3c.png)

2. Seleccionaremos la ruta de descarga y esperaremos a que esta concluya.

3. Una vez descargado el archivo daremos clic derecho sobre él y daremos clic en "extraer en spring-tool-suite-4-4.18.0.RELEASE-e4.27.0-win32.win32.x86_64.self-extracting\"

4. Nos dejará una carpeta que abriremos.

![image](https://user-images.githubusercontent.com/106614143/232861497-57909d55-f11f-4e8c-877c-88369ce87a46.png)

5. Daremos clic derecho en contents y luego en extraer en "contents\", esto nos dejará una carpeta que abriremos.

![image](https://user-images.githubusercontent.com/106614143/232861802-719588f3-435b-41f5-8997-31024bc9b2ae.png)

6. Entraremos en la carpeta sts-4.18.0.RELEASE

![image](https://user-images.githubusercontent.com/106614143/232861917-63b3efe0-9c1d-4e03-8ab1-add6d73131aa.png)

7. Ejecutaremos el SpringToolStuite4 de tipo Aplicación.

![image](https://user-images.githubusercontent.com/106614143/232862030-c31d139b-7a2d-420b-9f16-2c72383eac0c.png)

Y ya tendríamos el SpringToolSuite4 funcionando.

## Clonar el proyecto

1.	Para clonar el proyecto crearemos una carpeta y en esta abriremos una terminal del sistema en la que escribiremos el comando “git clone https://github.com/jantorres53/Ittiva.git” y esperaremos a que termine de descargarse el proyecto.

![image](https://user-images.githubusercontent.com/106614143/232639865-51aca498-762c-4548-97e4-6c82ed8582aa.png)
![image](https://user-images.githubusercontent.com/106614143/232639932-d4d31d2f-2d1b-4355-8f34-ff50453096a2.png)

# Guía

## Proceso de instalación para el Front-end

2.	Abriremos la carpeta que nos descargó el paso anterior y abriremos una terminal nueva, después escribiremos el comando “npm i” para que descargue todas las dependencias utilizadas y esperaremos a que termine el proceso.

![image](https://user-images.githubusercontent.com/106614143/232641763-5e7dca67-f32c-4d56-9fad-16420692cb67.png)
![image](https://user-images.githubusercontent.com/106614143/232641772-5194fa84-069f-40c7-b7eb-12ac2a871201.png)

3. Después de esto se tendrá que ejecutar el comando “ng s” y esperaremos a que finalice el proceso.

![image](https://user-images.githubusercontent.com/106614143/232640374-10268290-037b-4351-8458-4732e2e0995f.png)
![image](https://user-images.githubusercontent.com/106614143/232640477-731d7185-5e50-459d-9008-c2139679b4ea.png)

4.	Abriremos el navegador y escribiremos en la barra de búsqueda la siguiente ruta: “localhost:4200”.

![image](https://user-images.githubusercontent.com/106614143/232641833-4d93699f-50a5-42e5-b65e-0ea90638e5a7.png)

## Proceso de instalación para el Back-end

5.	Para realizar la instalación del sistema, necesitaremos descargar el archivo de back-end del siguiente repositorio al igual que el front-end con el comando “git clone https://github.com/JorgeADnro/Back-End-Integradora.git”.

![image](https://user-images.githubusercontent.com/106614143/232641931-ddec9f20-3795-405d-a96b-3b52001109f8.png)
![image](https://user-images.githubusercontent.com/106614143/232641944-38c45ed5-1351-4bed-b58d-75455ccc40ea.png)

6.	Luego utilizaremos la herramienta “Spring tool suite 4” para abrir el archivo dando clic en File, luego en Open Project from File System.

![image](https://user-images.githubusercontent.com/106614143/232641967-b4be68a2-e3f5-4ddf-9028-91cbfc92a445.png)

7. Procederemos a dar clic en “Import” y seleccionaremos la carpeta que dice General y luego en Projects from Folder Archive.

![image](https://user-images.githubusercontent.com/106614143/232642040-3ec1d470-f267-4467-b7a2-f22a95577dc6.png)

8. Procederemos a dar clic en “Directory…” y seleccionaremos la carpeta donde se clonó el proyecto, luego de eso daremos clic en Finish.

![image](https://user-images.githubusercontent.com/106614143/232642101-68fb9676-b285-4885-8d7b-346d60d2c514.png)

9.Una vez abierto el proyecto en la parte inferior izquierda daremos clic en local y daremos en (Re)start.

![image](https://user-images.githubusercontent.com/106614143/232642075-f4bd6ed2-ceb8-40bd-809b-ec751d4e915d.png)

10. Al momento de ejecutar la opción, se ejecutará el servicio y podremos usar el proyecto normalmente.

![image](https://user-images.githubusercontent.com/106614143/232642122-08a1241c-f2e9-48ed-a4a6-1514b45e911c.png)


Si haz seguido todos los pasos, entonces tendrás el proyecto funcionando correctamente.

## Manual de usuario

1. Un administrador y un recepcionista pueden iniciar sesión en el sistema.

![image](https://user-images.githubusercontent.com/106614143/232942065-dad81b6f-9b9d-4fb4-9c21-78235cd02fa6.png)
![image](https://user-images.githubusercontent.com/106614143/232942090-77074bcf-fdb0-4550-a6fe-4098270ca612.png)

2. Un administrador puede registrar nuevos empleados (Se creó al recepcionista llamado Pedro).

![image](https://user-images.githubusercontent.com/106614143/232942155-fa78884f-a075-4c48-9e7e-0ba0f9e49f4f.png)

3. Un recepcionista *NO* puede registrar nuevos empleados (Se inició sesión como Pedro).

![image](https://user-images.githubusercontent.com/106614143/232942306-2438d37a-b157-48fe-8468-374861558dcf.png)

4. El administrador, un recepcionista y un usuario pueden ver los detalles de un cliente.

![image](https://user-images.githubusercontent.com/106614143/232942393-32970422-4e58-4edf-9ff9-72bb6506a782.png)

5. El administrador y un recepcionista pueden crear un cliente.

![image](https://user-images.githubusercontent.com/106614143/232942475-dad3b2c5-ec1b-4aac-b043-3eec452a0d8b.png)
![image](https://user-images.githubusercontent.com/106614143/232942513-c3ae8088-b5da-47a3-a4ed-9887bc1a1abb.png)

6. El administrador y un recepcionista pueden actualizar los datos de un cliente (Se dió clic en el botón Editar de la lista de clientes).

![image](https://user-images.githubusercontent.com/106614143/232942594-ad6d96a4-ee2a-40d9-aef1-a43f000fe48e.png)
![image](https://user-images.githubusercontent.com/106614143/232942653-872cdc6f-f960-4b39-a7e5-57681cebb482.png)

7. El administrador y un recepcionista pueden eliminar un cliente (Se dió clic en el botón Eliminar de la lista de clientes).

![image](https://user-images.githubusercontent.com/106614143/232942719-1e631eac-cf80-419b-945e-094236f56612.png)
![image](https://user-images.githubusercontent.com/106614143/232942760-00a417fd-7319-4301-8107-79c16dd1c876.png)


## Participantes
* [Jorge Luis Ayala Manrique](https://github.com/JorgeADnro)
* [Omar Ricardo Garay Garcia](https://github.com/Ricardo7173)
* [Juan Antonio Rincon Torres](https://github.com/jantorres53)
* [Angel Fernando Sevilla Hernandez](https://github.com/FerchaSS)
