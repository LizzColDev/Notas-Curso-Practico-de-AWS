# Curso Práctico de AWS

Created: June 21, 2023 5:17 PM

<details>
  <summary><b>¿Qué es el cómputo en la nube?</b></summary>
    
![image1](https://github.com/LizzColDev/Notas-Curso-Practico-de-AWS/blob/main/Curso%20Pr%C3%A1ctico%20de%20AWS%2024475480c49a4f56b305349b6a8e131b/Untitled.png)
    
El cómputo en la nube, también conocido como cloud computing, se refiere a la entrega de servicios de computación a través de Internet. AWS (Amazon Web Services) es un proveedor líder de servicios de cómputo en la nube que ofrece una amplia gama de servicios y herramientas para ayudar a las empresas a implementar, escalar y administrar sus aplicaciones y recursos en la nube.
    
AWS proporciona servicios de infraestructura como servicio (IaaS), plataforma como servicio (PaaS) y software como servicio (SaaS). Algunos de los servicios más destacados de AWS incluyen:
    
1. Amazon Elastic Compute Cloud (EC2): Permite a los usuarios alquilar instancias de servidores virtuales para ejecutar aplicaciones y cargas de trabajo en la nube.
2. Amazon Simple Storage Service (S3): Es un servicio de almacenamiento en la nube altamente escalable y duradero, diseñado para almacenar y recuperar grandes cantidades de datos desde cualquier ubicación en la web.
3. Amazon Relational Database Service (RDS): Proporciona una gestión y despliegue sencillos de bases de datos relacionales, como MySQL, Oracle, SQL Server y PostgreSQL, en la nube.
4. Amazon Lambda: Es un servicio de cómputo sin servidor que permite ejecutar código sin aprovisionar ni administrar servidores.
5. Amazon Elastic Beanstalk: Permite a los desarrolladores implementar y administrar fácilmente aplicaciones web utilizando diferentes lenguajes de programación, plataformas y servicios de AWS.
6. Amazon Virtual Private Cloud (VPC): Proporciona una red virtual aislada en la nube de AWS, lo que permite a los usuarios controlar y personalizar su entorno de red.
    
Estos son solo algunos ejemplos de los servicios que ofrece AWS para el cómputo en la nube. Utilizando estos servicios, las organizaciones pueden aprovechar la infraestructura y los recursos de computación de AWS sin necesidad de adquirir y administrar su propia infraestructura física, lo que les permite ahorrar costos, escalar fácilmente y enfocarse en el desarrollo y la implementación de sus aplicaciones.

</details> 

<details>
  <summary><b>¿Cómo puedo empezar a usar AWS?</b></summary>    

Para empezar a usar AWS, primero debes crear una cuenta de AWS y luego configurar tus servicios y recursos en la nube. Puedes hacerlo a través del sitio web de AWS o mediante la línea de comandos de AWS. Una vez que hayas configurado tus servicios, podrás acceder a ellos a través del panel de control de AWS o mediante la API de AWS. También puedes usar AWS Marketplace para encontrar y comprar aplicaciones y servicios de terceros para usar en tu infraestructura de AWS. 
    
Para crear tu cuenta de AWS debes entrar a [aws.amazon.com](https://aws.amazon.com/), recuerda que para crear tu contraseña puedes usar [passwordsgenerator.net](https://passwordsgenerator.net/).
    
AWS dispone de dos programas que permiten a los clientes trasladar sus enseñanzas y esfuerzos de investigación a la nube y de este modo innovar más rápidamente y con un menor costo. Para aplicar a las becas de AWS entra a [aws.amazon.com/es/grants](https://aws.amazon.com/es/grants/).
    
Cuando tengas tu cuenta registrada, entra a [console.aws.amazon.com](https://console.aws.amazon.com/) y tendrás acceso a la consola de amazon con todos los servicios disponibles.

</details>    

<details>
  <summary><b>Introducción a la oferta de servicios de AWS y sus aplicaciones</b></summary>   

AWS ofrece una amplia variedad de servicios de cómputo en la nube, que incluyen servicios de infraestructura como servicio (IaaS), plataforma como servicio (PaaS) y software como servicio (SaaS). Algunos de los servicios más destacados son:
    
- Amazon Elastic Compute Cloud (EC2): permite alquilar instancias de servidores virtuales para ejecutar aplicaciones y cargas de trabajo en la nube.
- Amazon Simple Storage Service (S3): es un servicio de almacenamiento en la nube altamente escalable y duradero, diseñado para almacenar y recuperar grandes cantidades de datos desde cualquier ubicación en la web.
- Amazon Relational Database Service (RDS): proporciona una gestión y despliegue sencillos de bases de datos relacionales, como MySQL, Oracle, SQL Server y PostgreSQL, en la nube.
- Amazon Lambda: es un servicio de cómputo sin servidor que permite ejecutar código sin aprovisionar ni administrar servidores.
- Amazon Elastic Beanstalk: permite implementar y administrar fácilmente aplicaciones web utilizando diferentes lenguajes de programación, plataformas y servicios de AWS.
- Amazon Virtual Private Cloud (VPC): proporciona una red virtual aislada en la nube de AWS, lo que permite a los usuarios controlar y personalizar su entorno de red.
    
Estos son solo algunos ejemplos de los servicios que ofrece AWS para el cómputo en la nube. Utilizando estos servicios, las organizaciones pueden aprovechar la infraestructura y los recursos de computación de AWS sin necesidad de adquirir y administrar su propia infraestructura física, lo que les permite ahorrar costos, escalar fácilmente y enfocarse en el desarrollo y la implementación de sus aplicaciones.

</details>
<details>
  <summary><b>Ejemplo de arquitectura con Elastic Beanstalk</b></summary>   

1. Aplicación web: Supongamos que deseas implementar una aplicación web basada en un lenguaje de programación como Python, Java o Node.js.

2. Código de la aplicación: Tienes tu código fuente de la aplicación web listo para ser implementado. Puede incluir archivos HTML, CSS, JavaScript y archivos de servidor según el lenguaje de programación que estés utilizando.
3. Elastic Beanstalk: Utilizarás AWS Elastic Beanstalk como el servicio de implementación y administración de aplicaciones. Elastic Beanstalk te permite simplificar la implementación y la gestión de tu aplicación web.
4. Entorno de Elastic Beanstalk: Crearás un entorno de Elastic Beanstalk para tu aplicación. Un entorno puede consistir en una instancia de servidor o una agrupación de instancias de servidor, dependiendo de los requisitos de tu aplicación.
5. Configuración del entorno: Configurarás el entorno de Elastic Beanstalk según tus necesidades. Esto incluye la selección del lenguaje de programación, la elección del entorno de ejecución (por ejemplo, Apache HTTP Server o Nginx), la configuración de variables de entorno y la configuración de la capacidad de escalado automático.
6. Implementación de la aplicación: Subirás tu código fuente de la aplicación a Elastic Beanstalk. Puedes hacer esto a través de la interfaz de usuario de Elastic Beanstalk o utilizando herramientas de línea de comandos.
7. Configuración de la base de datos: Si tu aplicación web requiere una base de datos, puedes configurar y utilizar servicios como Amazon RDS (Relational Database Service) para alojar tu base de datos.
8. Configuración de almacenamiento: Si tu aplicación necesita almacenar archivos, puedes utilizar servicios como Amazon S3 (Simple Storage Service) para el almacenamiento de objetos.
9. Escalado y monitoreo: Elastic Beanstalk puede ajustar automáticamente la capacidad de tu entorno en función de la carga de la aplicación. También puedes configurar alarmas y monitorear el rendimiento de tu aplicación utilizando servicios como Amazon CloudWatch.
10. Implementación continua: Puedes integrar Elastic Beanstalk con herramientas de integración continua y entrega continua (CI/CD) para automatizar el proceso de implementación de tu aplicación y realizar actualizaciones continuas.
    
Esta es solo una arquitectura básica y puedes personalizarla según tus necesidades específicas. Elastic Beanstalk te proporciona una manera fácil de implementar, administrar y escalar tu aplicación web en AWS sin tener que preocuparte por la infraestructura subyacente.
   
</details>    

<details>
  <summary><b>¿Qué es Amazon EC2?</b></summary>   


Amazon EC2 (Elastic Compute Cloud) es un servicio de AWS (Amazon Web Services) que proporciona capacidad informática escalable en la nube. Es uno de los servicios fundamentales de AWS y se utiliza para alojar y ejecutar aplicaciones en servidores virtuales conocidos como "instancias".
    
En términos sencillos, Amazon EC2 te permite alquilar servidores virtuales en la nube para ejecutar tus aplicaciones y cargas de trabajo. Puedes elegir entre una amplia variedad de configuraciones de instancias, como el tipo de instancia, la cantidad de CPU, la memoria, el almacenamiento y el sistema operativo.
    
Con Amazon EC2, obtienes varios beneficios:
    
1. Escalabilidad: Puedes escalar fácilmente la capacidad de tus instancias de EC2 hacia arriba o hacia abajo según tus necesidades. Puedes agregar o eliminar instancias según la carga de trabajo de tu aplicación, lo que te permite ajustar la capacidad de forma flexible y eficiente.

2. Flexibilidad: EC2 te ofrece una amplia selección de tipos de instancias para adaptarse a diferentes casos de uso y requisitos de rendimiento. Puedes elegir entre instancias de propósito general, optimizadas para CPU, para memoria, para almacenamiento y muchas otras opciones especializadas.
3. Control total: Tienes control total sobre tus instancias de EC2. Puedes configurar el sistema operativo, instalar y administrar software adicional, y personalizar la configuración según tus necesidades específicas. Esto te permite crear entornos de desarrollo personalizados y ejecutar aplicaciones de manera más flexible.
4. Alta disponibilidad y fiabilidad: EC2 te ofrece opciones para implementar tus instancias en múltiples zonas de disponibilidad, lo que brinda redundancia y mayor disponibilidad para tus aplicaciones. Además, Amazon EC2 ofrece características de almacenamiento duradero y replicado para proteger tus datos.
5. Integración con otros servicios de AWS: Amazon EC2 se integra perfectamente con otros servicios de AWS, lo que te permite aprovechar una amplia gama de servicios adicionales, como almacenamiento en la nube (Amazon S3), bases de datos (Amazon RDS), servicios de red (Amazon VPC) y mucho más.
    
En resumen, Amazon EC2 es un servicio de AWS que te permite alquilar servidores virtuales en la nube, lo que te brinda flexibilidad, escalabilidad y control total sobre tus aplicaciones y cargas de trabajo. Puedes ejecutar una amplia variedad de aplicaciones, desde sitios web y aplicaciones empresariales hasta análisis de datos y procesamiento en lotes.

</details>    

<details>
  <summary><b>Creando una instancia de EC2</b></summary>   


1. Inicia sesión en la Consola de administración de AWS en **[https://console.aws.amazon.com/](https://console.aws.amazon.com/)**.
    
2. Ve al servicio EC2 haciendo clic en "Servicios" en la parte superior y seleccionando "EC2" bajo la sección "Compute" o buscando "EC2" en la barra de búsqueda.
3. En el panel de navegación izquierdo, haz clic en "Instancias" y luego en "Launch instances" (Crear instancias).
4. Paso 1: Elige una imagen de AMI (Amazon Machine Image):
    - Selecciona la AMI que mejor se adapte a tus necesidades. Puedes elegir entre imágenes predefinidas proporcionadas por AWS o imágenes personalizadas que hayas creado previamente.
5. Paso 2: Elige un tipo de instancia:
    - Selecciona el tipo de instancia que mejor se adapte a tus requerimientos de capacidad de CPU, memoria y almacenamiento.
6. Paso 3: Configurar detalles de la instancia:
    - Aquí puedes configurar opciones adicionales, como el número de instancias que deseas crear, la red virtual (VPC), la subred, las asignaciones de IP, entre otros. Puedes dejar las opciones predeterminadas o personalizarlas según tus necesidades.
7. Paso 4: Añadir almacenamiento:
    - Configura el almacenamiento de tu instancia. Puedes agregar volúmenes EBS (Elastic Block Store) y especificar el tamaño y el tipo de cada uno.
8. Paso 5: Configurar grupo de seguridad:
    - Aquí puedes seleccionar un grupo de seguridad para tu instancia. Los grupos de seguridad son conjuntos de reglas de firewall que controlan el tráfico de red hacia y desde tu instancia.
9. Paso 6: Revisar y lanzar:
  - Revisa todas las configuraciones realizadas hasta el momento y asegúrate de que sean correctas. Puedes realizar cambios si es necesario. Luego, haz clic en "Launch" (Lanzar).
10. Selecciona una clave existente o crea una nueva:
    - Selecciona una clave SSH existente o crea una nueva. Esto te permitirá acceder a tu instancia de EC2 mediante SSH.
11. Haz clic en "Launch instances" (Lanzar instancias) y la instancia de EC2 se creará.
    
Una vez creada la instancia, podrás verla en la lista de instancias de EC2 en la consola de administración de AWS. Podrás acceder a ella utilizando la clave SSH asociada y configurarla según tus necesidades, instalando software, configurando servicios, etc.

</details>     
<details>
  <summary><b>Subiendo un proyecto: Clonando un repositorio de GitHub a nuestra Instancia de EC2</b></summary>   
    
    👉 <b>Nota</b>: Antes de comenzar, asegúrate de tener una instancia de EC2 creada y configurada. También debes tener acceso a tu cuenta de GitHub y a la consola de administración de AWS.
    
Para clonar un repositorio de GitHub a tu instancia de EC2, sigue estos pasos:
    
1. Accede a tu instancia de EC2 utilizando SSH. Puedes hacerlo utilizando una herramienta como PuTTY o la terminal de tu sistema operativo.
    
2. Una vez que te hayas conectado a tu instancia de EC2, asegúrate de tener Git instalado. Puedes verificar si Git está instalado escribiendo `git --version` en la línea de comandos. Si Git no está instalado, puedes instalarlo escribiendo `sudo yum install git`.
3. Clona el repositorio de GitHub en tu instancia de EC2. Para ello, escribe el siguiente comando en la línea de comandos:
        
        `git clone <URL del repositorio de GitHub>`
        
Reemplaza `<URL del repositorio de GitHub>` con la URL del repositorio que deseas clonar. Por ejemplo, si el repositorio se llama `mi-proyecto` y está en la cuenta de GitHub `mi-cuenta`, la URL del repositorio sería `https://github.com/mi-cuenta/mi-proyecto.git`.
        
4. Si el repositorio es privado, es posible que debas autenticarte con tu cuenta de GitHub. Si es así, Git te pedirá tus credenciales de GitHub.
5. Una vez que Git haya clonado el repositorio, puedes acceder a él en tu instancia de EC2 y trabajar en él como lo harías en cualquier otra máquina. Puedes ejecutar comandos como `git pull` para obtener las últimas actualizaciones del repositorio, o `git push` para enviar tus cambios de vuelta a GitHub.
    
Siguiendo estos pasos, podrás clonar cualquier repositorio de GitHub en tu instancia de EC2 y trabajar en él directamente desde la nube.

</details>     
 
<details>
  <summary><b>Subiendo un proyecto a nuestra instancia de EC2: Ejecutar nuestro proyecto</b></summary>   

    👉 <b>Nota</b>: Antes de comenzar, asegúrate de tener una instancia de EC2 creada y configurada. También debes tener acceso a tu cuenta de GitHub y a la consola de administración de AWS.
    
Para ejecutar un proyecto en tu instancia de EC2, sigue estos pasos:
    
1. Accede a tu instancia de EC2 utilizando SSH. Puedes hacerlo utilizando una herramienta como PuTTY o la terminal de tu sistema operativo.

2. Una vez que te hayas conectado a tu instancia de EC2, asegúrate de tener Git instalado. Puedes verificar si Git está instalado escribiendo `git --version` en la línea de comandos. Si Git no está instalado, puedes instalarlo escribiendo `sudo yum install git`.
3. Clona el repositorio de GitHub en tu instancia de EC2. Para ello, escribe el siguiente comando en la línea de comandos:
        
        `git clone <URL del repositorio de GitHub>`
        
Reemplaza `<URL del repositorio de GitHub>` con la URL del repositorio que deseas clonar. Por ejemplo, si el repositorio se llama `mi-proyecto` y está en la cuenta de GitHub `mi-cuenta`, la URL del repositorio sería `https://github.com/mi-cuenta/mi-proyecto.git`.
        
4. Si el repositorio es privado, es posible que debas autenticarte con tu cuenta de GitHub. Si es así, Git te pedirá tus credenciales de GitHub.
5. Una vez que Git haya clonado el repositorio, accede a la carpeta del proyecto y verifica si hay algún archivo README o documento de instrucciones para la ejecución del proyecto.
6. Si hay algún archivo de instrucciones, sigue las instrucciones para ejecutar el proyecto. Si no hay instrucciones, probablemente debas compilar y ejecutar el proyecto utilizando algún lenguaje de programación. Consulta la documentación del lenguaje de programación para obtener más información.
7. Si el proyecto utiliza algún servicio de AWS, asegúrate de configurar las credenciales y permisos adecuados para que el proyecto pueda acceder a los recursos de AWS necesarios.
8. Una vez que hayas ejecutado el proyecto, comprueba que funciona correctamente. Puedes hacerlo accediendo a la URL del proyecto en un navegador web o utilizando alguna herramienta de prueba automatizada.
    
Siguiendo estos pasos, podrás ejecutar cualquier proyecto en tu instancia de EC2 y trabajar en él directamente desde la nube.
    
</details>    

<details>
  <summary><b>¿Qué es Lambda y Serverless?</b></summary>   

![Untitled](https://github.com/LizzColDev/Notas-Curso-Practico-de-AWS/blob/main/Curso%20Pr%C3%A1ctico%20de%20AWS%2024475480c49a4f56b305349b6a8e131b/Untitled%201.png)
    
![Untitled](https://github.com/LizzColDev/Notas-Curso-Practico-de-AWS/blob/main/Curso%20Pr%C3%A1ctico%20de%20AWS%2024475480c49a4f56b305349b6a8e131b/Untitled%202.png)
    
![Untitled](https://github.com/LizzColDev/Notas-Curso-Practico-de-AWS/blob/main/Curso%20Pr%C3%A1ctico%20de%20AWS%2024475480c49a4f56b305349b6a8e131b/Untitled%203.png)
    
- Notas:
        
Lambda es un proyecto de AWS muy relacionado con el concepto de *[Serverless](https://platzi.com/blog/introduccion-a-serverless-framework/)*, dejar la administración de tus servidores en manos de Amazon para solo encargarte de las funciones de código que ejecutara tu aplicación.
        
## ¿Qué son?
        
Imagina lambda como un lugar donde puedes ejecutar funciones de tu código.
        
## Serverless
        
No existe un servidor como vimos en EC2, es decir, solo está el código en lamba y AWS se encarga de ejecutarlo cuando necesites.
        
## Lenguajes soportados
        
Puedes programar funciones lamba en Nodejs (JavaScript), Python, Java (8), C# (.Net Core) y Go.
        
Recuerda tener en cuenta los siguientes puntos:
        
- **Memoria**: Mínima de 128MB, máxima 3000MB con incrementos de 64MB.
- **Límites** de ejecución y espacio: Puedes correr tu aplicación hasta 300 segundos y tienes un `/tmp` limitado a 512MB.
- **Ejecución paralela**: Esta limitada a 1000 ejecuciones concurrentes (a un mismo tiempo), no tiene límite en ejecuciones secuenciales (una detrás de otra).
        
## Ventajas de Lambda:
        
- **Seguridad**: Al ser una infraestructura compartida, no tienes que preocuparte de seguridad: AWS maneja todo.
- **Performance**: AWS está monitoreando constantemente la ejecución de tus funciones y se encarga de que siempre tenga el mejor performance.
- **Código aislado**: Tu código, aún estando en una infraestructura compartida, corre en un ambiente virtual exclusivo, aislado de las demás ejecuciones lamba.
        
Recuerda que AWS te regala 1 millón de peticiones lamba gratis el primer año.
        
Seguridad: AWS Lambda y los servicios serverless en general se benefician de las medidas de seguridad proporcionadas por el proveedor de servicios en la nube. AWS Lambda ofrece integración con los servicios de seguridad de AWS, como AWS Identity and Access Management (IAM) para la gestión de permisos y políticas, y AWS Key Management Service (KMS) para el cifrado de datos.
        
Rendimiento: AWS Lambda y los servicios serverless son altamente escalables y ofrecen un rendimiento eficiente. Los proveedores de servicios en la nube gestionan automáticamente el escalado de recursos subyacentes para satisfacer la demanda de ejecución de código. Además, se paga solo por el tiempo de ejecución real del código, lo que permite una utilización eficiente de los recursos y un rendimiento rápido en función de la demanda.
        
Código aislado: Cada función de Lambda se ejecuta en un entorno aislado, lo que significa que no hay interferencia entre diferentes funciones. Esto garantiza que el código y los recursos utilizados por una función no afecten a otras funciones. Cada función de Lambda tiene su propio espacio de ejecución y recursos asignados.
        
En resumen, Lambda y Serverless ofrecen un modelo de programación sin servidor donde los desarrolladores pueden ejecutar código en la nube sin preocuparse por la infraestructura subyacente. Se admiten varios lenguajes de programación, se proporciona seguridad a través de la integración con servicios de seguridad de la nube y se benefician del rendimiento escalable y el aislamiento de código para una ejecución eficiente y segura.
        
</details>    

<details>
  <summary><b>Creando una función Lambda</b></summary>   

Para crear una función Lambda en AWS, sigue los siguientes pasos:
    
1. Accede a la Consola de administración de AWS: **[https://console.aws.amazon.com/](https://console.aws.amazon.com/)**
    
2. Haz clic en "Servicios" en la parte superior de la página y luego busca "Lambda" en el campo de búsqueda.
3. Haz clic en "Lambda" para acceder al servicio AWS Lambda.
4. Haz clic en el botón "Crear función" para comenzar a crear una nueva función Lambda.
5. Selecciona el método de autoría de la función:
   - "Autor desde cero": Puedes escribir el código de la función directamente en el editor de la consola de Lambda.
    - "Usar un patrón de ejemplo": Puedes seleccionar un patrón predefinido para crear una función basada en casos de uso comunes.
    - "Usar un archivo .zip": Puedes cargar un archivo ZIP que contenga el código fuente de la función.
    - "Usar un archivo .jar": Puedes cargar un archivo JAR que contenga el código fuente de la función (para funciones escritas en Java).
    - "Contenedor": Puedes crear una función Lambda utilizando un contenedor de Docker.
6. Proporciona un nombre para la función Lambda y selecciona un tiempo de ejecución. El tiempo de ejecución define el entorno de ejecución en el que se ejecutará tu función (por ejemplo, Python, Node.js, Java, etc.).
7. Configura las opciones de función según tus necesidades, como asignación de recursos, configuración de permisos y configuración de variables de entorno.
8. En la sección "Código de función", escribe o carga el código fuente de la función.
9. Haz clic en el botón "Crear función" para finalizar la creación de la función Lambda.
    
Una vez creada la función Lambda, puedes probarla utilizando eventos de prueba, configurar disparadores para que se ejecute en respuesta a eventos específicos y administrar su configuración y monitoreo a través de la consola de Lambda.
    
Recuerda que estos pasos son generales y pueden variar ligeramente según la versión de la consola de administración de AWS. Siempre es recomendable consultar la documentación oficial de AWS para obtener instrucciones más detalladas y actualizadas.
    
</details>    
