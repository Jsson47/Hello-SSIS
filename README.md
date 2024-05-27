# Hello-SSIS
1. Descripción del Proyecto
SQL Server Integración Services (SSIS) es un componente de Microsoft SQL Server utilizado  principalmente para la integración de datos, que incluye la extracción, transformación y carga de  datos (ETL). SSIS ayuda a automatizar el flujo de trabajo en diversos procesos de gestión de datos.

El proyecto SSIS (SQL Server Integration Services) ha sido desarrollado para automatizar y optimizar los procesos de integración de datos en nuestros proyectos. Este proyecto facilita la extracción, transformación y carga (ETL) de datos desde múltiples fuentes a un almacén de datos centralizado.

2. Objetivos del Proyecto

Automatización: Reducir el esfuerzo manual involucrado en la integración de datos.
Eficiencia: Mejorar la velocidad y precisión de los procesos ETL.
Confiabilidad: Asegurar la consistencia y calidad de los datos.

4. Requisitos Previos

Antes de ejecutar el proyecto, asegúrate de tener lo siguiente:

SQL Server: Versión 2019 o superior.
SQL Server Data Tools (SSDT): Para editar y ejecutar los paquetes SSIS.
Extensión: SQL Server Integration Services Projects 2022
Almacenamiento y procesamiento de datos (Server Data Tools, Herramientas de desarrollo de .NET Framework 4.7)
SQL Server Management Studio 2019 (SSMS) y cambiar el status Enabled de protocolos Named Pipes, TCP/IP.
Permisos Adecuados: Acceso de lectura/escritura a las bases de datos y servidores implicados.

Proceso de Instalación y Ejecución.
Hello-SSIS / Flujo de trabajo.
Clona el repositorio desde GitHub.
Crear con anticipacion la base datos SSISIntro
Ejecutar el paquete llamado "ImportarXMLFile" (SQL Task Disable debido a que hay un importar datos y no 
pueden estar activas al mismo tiempo, se encuentra desactivado pero configifurado).
Visualizar la caga de datos con un Select en la tabla.



