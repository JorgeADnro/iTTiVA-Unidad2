# iTTiVA-Unidad2

## Contenido
<details>
  <summary>Tabla contenido</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#organigrama">Organigrama</a></li>
        <li><a href="#diagrama-gantt">Diagrama Gantt</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#requerimientos">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#modelo-relacional">Modelo Relacional</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de Clases</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
        <li><a href="#diagrama-de-actividadess">Diagrama de Actividades</a></li>
      </ul>
    </li>          
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
        <li><a href="#ejecución">Ejecución</a></li>
      </ul>
    </li>       
    <li><a href="#guias">Guias</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
#### Acerca del proyecto
Nombre del proyecto 
* iTTiVA Project

Requisitos.
* Internet 
* Equipo de computo 
* Tener instalado Angular
* Tener instalado Node JS
* Tener instalado Visual Studio Code 

<!-- Descripción -->
#### Descripción.
La gestión de usuario y gestión de privilegios resulta una parte fundamental en un sistema de administrativo para un
Gimnasio, tomando en cuenta que la principal idea de este es llevar un control absoluto sobre todo lo que lo rodea
como sus clientes, empleados y los roles con los que cuenta cada uno. Es por ello que en este documento se
mostraran la descripción de los objetivos, características y funcionalidades de cada uno de ellos.

Gestion de Usuario
Objetivos:
➢ Administrar lo que puede llevar a cabo cada usuario.
➢ Controlar la cantidad de usuarios registrados en el sistema.
➢ Controlar los roles con los que cuentan lo usuarios.

Características:
➢ Utiliza un sistema de asignación de roles al usuario, el rol trae con los diferentes privilegios
dependiendo el rol.
➢ Permite la realización de diferentes actividades dependiendo del rol.

Funcionalidades:
➢ Creación, actualización, eliminación y búsqueda de un determinado usuario.
➢ Asignación de los diferentes roles.
➢ Creación de nuevos roles con diferentes privilegios.

Gestión de Privilegios
Objetivos:
➢ Controlar con los privilegios con los que puede contar cada usuario dependiendo el rol.
➢ Definir y gestionar los roles y responsabilidades de cada empleado.
➢ Asignar permisos y accesos al sistema.
➢ Controlar y monitorear el acceso a información confidencial del gimnasio.

Características:
➢ Permite la definición de roles y permisos personalizados para cada empleado.
➢ Permite la asignación de permisos y accesos al sistema.
➢ Facilita el monitoreo del acceso a información confidencial del gimnasio.
➢ Garantiza la seguridad de la información mediante la restricción de accesos.

Funcionalidades:
➢ Definición y gestión de roles y permisos personalizados para cada empleado.
➢ Asignación de permisos y accesos al sistema.
➢ Monitoreo del acceso a información confidencial del gimnasio.
➢ Restricción de accesos a información confidencial para garantizar la seguridad de la información.

Casos de Uso
![image](https://user-images.githubusercontent.com/123588637/232643366-795855d4-9359-44bd-aa17-5961fb64125c.png)
![image](https://user-images.githubusercontent.com/123588637/232643387-e3421ba1-2e74-4c70-9cdb-2f9100c763a8.png)
![image](https://user-images.githubusercontent.com/123588637/232643422-884202a4-ca0f-4d0c-9006-d74da3506bf6.png)
![image](https://user-images.githubusercontent.com/123588637/232643460-c6e6da54-cad2-462d-88f3-56ae9ed3920a.png)
![image](https://user-images.githubusercontent.com/123588637/232643486-806862c0-8985-4f84-aea1-ae44906cab29.png)
![image](https://user-images.githubusercontent.com/123588637/232643515-b0234f0c-41da-4cb7-ab19-ffda99548342.png)

Historias de Usuario
Historia de usuario Gestión de Usuario.
El usuario administrador ingresara al sistema a través de su usuario y contraseña ingresando al módulo de Usuarios
en donde tendrá tres opciones: agregar usuario, actualizar usuario y eliminar usuario, estas opciones permiten que el
administrador asigne, actualice y elimine los usuarios del gimnasio.

![image](https://user-images.githubusercontent.com/123588637/232643589-6f34b8c1-a5cb-4f3a-919d-84f42073308f.png)

Historia de usuario Gestión de Privilegios.
El usuario administrador ingresara al sistema a través de su usuario y contraseña ingresando al módulo de Usuarios
en donde tendrá las opciones de asignarle un rol a determinado empleado o usuario permiten que el administrador
asigne, actualice y elimine los roles por lo tanto los privilegios del gimnasio.

![image](https://user-images.githubusercontent.com/123588637/232643662-1f8e82a9-01b6-44ab-819b-08bef73cd8b7.png)

Diagrama de Actividades
![image](https://user-images.githubusercontent.com/123588637/232643724-29d8fa10-e6bc-4fbe-aad5-e56c82253c9f.png)
![image](https://user-images.githubusercontent.com/123588637/232644002-8d9ab609-d1ef-459a-9d16-aec70635aee6.png)
![image](https://user-images.githubusercontent.com/123588637/232644059-8c8482fb-17d8-4375-b3b0-955637433a5f.png)
![image](https://user-images.githubusercontent.com/123588637/232644135-eeaef988-0c8e-4b0c-bf61-aeead52eb4ec.png)
![image](https://user-images.githubusercontent.com/123588637/232644159-f4d05ce2-cae5-4c21-ade6-08b0b30d4aec.png)
![image](https://user-images.githubusercontent.com/123588637/232644181-5928b937-5e81-449d-8b27-203a28ca730a.png)
![image](https://user-images.githubusercontent.com/123588637/232644360-a9cb7d3a-1e27-498c-b160-8b5edbe5dac2.png)
![image](https://user-images.githubusercontent.com/123588637/232644387-70e1a283-7b0c-47a1-a4aa-3abd8cefe4ea.png)

<!-- Modelo Arquitectura MVC -->
## Modelo Arquitectura MVC

•	El usuario realiza una solicitud a nuestro sitio web. Generalmente estará desencadenada por acceder a una página de nuestro sitio. Esa solicitud le llega al controlador. 
•	El controlador comunica tanto con modelos como con vistas. A los modelos les solicita datos o les manda realizar actualizaciones de los datos. A las vistas les solicita la salida correspondiente, una vez se hayan realizado las operaciones pertinentes según la lógica del negocio. 
•	Para producir la salida, en ocasiones las vistas pueden solicitar más información a los modelos. En ocasiones, el controlador será el responsable de solicitar todos los datos a los modelos y de enviarlos a las vistas, haciendo de puente entre unos y otros. Sería corriente tanto una cosa como la otra, todo depende de nuestra implementación; por eso esa flecha la hemos coloreado de otro color. 
•	Las vistas envían al usuario la salida. Aunque en ocasiones esa salida puede ir de vuelta al controlador y sería éste el que hace el envío al cliente. 

Modelo MVC 
![image](https://user-images.githubusercontent.com/123511310/232640011-b8ccfdbc-7136-493b-993b-1e9a8c478c2a.png)

<!-- Modelo Arquitectura MVC -->
## Modelo de base de datos.

![image](https://user-images.githubusercontent.com/123511310/232651757-ede51409-1d00-491c-a7a2-d0f514e10c69.png)

## Estándar de base de datos.

Nombre de la colección en singular.
Nombre de los campos de cada colección sin incluir mayúsculas.
Nombre de la colección iniciando con mayúscula.
Se incluyen términos en ingles adecuados a la base de datos usada.
Si se incluye un dato tipo cadena, se usan comillas.

## Estándar de programación Camel Case.

Cuando un nombre del campo de la colección está constituido por dos palabras, se combinan estas palabras sin usar ningún carácter especial.
Comentarios incluidos al inicio con su nombre de clase respectivamente por cada uno.
Los nombres de las variables deben ser claros para saber el uso de cada una.
En los métodos se hace el uso de minúsculas únicamente.
Nombres de constantes en mayúsculas.


<!-- Objetivos -->
#### Objetivos.
El proyecto consiste en el rediseño de la página oficial de la empresa Optimen S.A de C.V. para incluir nuevas funcionalidades que brinden información actualizada sobre la empresa y sus avances en TI. Se busca lograr un sitio web altamente eficiente, con una rápida velocidad de carga para una navegación óptima. El administrador root podrá controlar los permisos de acceso de los usuarios, mientras que los creadores de contenido podrán crear, editar, eliminar y consultar noticias y eventos. Además, las noticias y eventos se mostrarán en la página principal para mantener a los usuarios visitantes informados acerca de las últimas novedades de la empresa.

<!-- Organigrama -->
#### Organigrama.
![image](https://user-images.githubusercontent.com/106614143/232810415-978b05e4-6990-4909-b8ea-27257fb7c7fc.png)


<!-- Diagrama Gantt -->
#### Diagrama Gantt.
![image]()


<!-- Análisis del proyecto -->
## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Requerimientos -->
#### Requerimientos.
![image]()

<!-- Diagrama de actividades -->
![image](https://user-images.githubusercontent.com/106614143/232811275-03c7dcb2-70fa-4953-b74a-b87b22ea77e6.png)


<!-- Diagrama de Casos de Uso -->
#### Diagrama Casos de Uso.
Creador de contenido
![image]()

Usuario visitante
![image]()

Administrador

![image]()


<!-- Diseño del proyecto -->
## Diseño de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Modelo Relacional -->
#### Modelo Relacional.
Esquema de la base de datos (nombre de campo, tipo de datos, restricciones, etc)
Colección eventos      
![image]()

Colección noticias     
![image]()

Colección de usuarios     
![image]()


<!-- Diagrama de Clases -->
#### Diagrama de Clases.
Evento 

![image]()

Noticias 

![image]()


<!-- Diagrama de Componentes -->
#### Diagrama de Componentes
Esquema de los componentes que interactúan (Modelo, Vista, Controlador, Servidor Web, Servidor de base de datos)

![image]()

#### Diagrama de actividades
Administrador root 
El administrador ingresa a la página, posteriormente inicia sesión si proporciona los datos correctos podrá dirigirse a él apartados y brindar permisos y asi mismo podra quitar los permisos, en caso de que el administrador no ingresos los datos correctos la autenticación presentara una falla en el sistema.

![image]()

Usuario visitante
El usuario visitante busca la página de optimen oficial y da clik sobre ella para entrar, tendrá la opción de navegar sin problemas dentro de la misma y poder abandonar la página.

![image]()

Creador de contenido
El creador de contenido ingresa a la página, posteriormente inicia sesión si proporciona los datos correctos podrá dirigirse a él apartado de agregar eventos o noticias nuevas, en caso de que el creador de contenido no ingrese los datos correctos la autenticación presentara una falla en el sistema y por lo tanto no podrá hacer modificaciones.

![image]()

<!-- Pruebas proyecto -->
## Pruebas.
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Casos de prueba -->
#### Casos de prueba.
Indicar los casos de prueba

<!-- Ejecución Casos de prueba -->
#### Ejecución.
Evidencia de Ejecución de Casos de prueba.


<!-- Iniciando -->
## Iniciando
Iniciando.

<!-- Requisitos -->
### Requisitos
Antes de utilizar las nuevas funcionalidades de administración de contenido del sitio web, se deben cumplir los siguientes requisitos previos:
*	Navegador web
*	Dispositivo electrónico
*	Permisos de usuario
*	Conexión a internet 
*	Edición de contenido


<!-- Instalación -->
### Proceso de instalación

## Clonar el proyecto

1.	Para clonar el proyecto crearemos una carpeta y en esta abriremos una terminal del sistema en la que escribiremos el comando “git clone https://github.com/jantorres53/Ittiva.git” y esperaremos a que termine de descargarse el proyecto.

![image](https://user-images.githubusercontent.com/106614143/232639865-51aca498-762c-4548-97e4-6c82ed8582aa.png)
![image](https://user-images.githubusercontent.com/106614143/232639932-d4d31d2f-2d1b-4355-8f34-ff50453096a2.png)

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


6.	Luego utilizaremos una herramienta llamada “Spring tool suite 4” para abrir el archivo dando clic en File, luego en Open Project from File System.

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



About-Us


## Participantes
* [Jorge Luis Ayala Manrique](https://github.com/JorgeADnro)
* [Omar Ricardo Garay Garcia](https://github.com/Ricardo7173)
* [Juan Antonio Rincon Torres](https://github.com/jantorres53)
* [Angel Fernando Sevilla Hernandez]
