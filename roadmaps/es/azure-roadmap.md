# Azure {#Azure}

Esta ruta de aprendizaje se centra en crear servicios alojados en Azure y acceder a ellos desde sus aplicaciones cliente de Xamarin. Los temas incluyen el portal de Azure, el servicio de aplicaciones móviles de Azure, la conexión a Azure desde un cliente móvil y la autenticación.

## Introducción a Azure (AZR101) {#introduction-azure}

> **Requisitos previos recomendados**: Introducción a Xamarin (XAM101)

Azure es la plataforma de computación en la nube del modelo de suscripción de Microsoft. Ofrece una amplia variedad de servicios de procesamiento, almacenamiento, redes y API. Este módulo le permite comenzar con Azure mediante una encuesta de varios de los servicios más populares y presentando el modelo de precios de Azure. A continuación, le muestra dos tareas principales: crear una cuenta de Azure y usar el portal web de Azure para aprovisionar un recurso como una máquina virtual.

### Enlaces útiles {#helpful-links-AZR101}

- [Crear una cuenta de Azure](https://docs.microsoft.com/es-es/learn/modules/create-an-azure-account/)
- [Documentación del portal de Azure](https://docs.microsoft.com/es-es/azure/azure-portal/)

### Explorando por su cuenta {#exploring-AZR101}

- [Guía de inicio para desarrolladores de Azure](https://docs.microsoft.com/es-es/azure/guides/developer/azure-developer-guide)
- [Documentación de aplicaciones móviles](https://docs.microsoft.com/es-es/azure/app-service-mobile/)
- [Xamarin y Azure](https://azure.microsoft.com/es-es/features/xamarin/)

## Creación de un servicio de aplicaciones móviles de Azure (AZR110) {#building-azure-mobile-app-service}

> **Requisitos previos recomendados**: Introducción a Azure (AZR101)

Muchas soluciones empresariales tienen necesidades similares: una base de datos para almacenar información, lógica del lado del servidor para procesar solicitudes de clientes y una API basada en REST para permitir el acceso de los clientes a los datos. Azure proporciona los componentes básicos para implementar todas estas funciones agrupadas bajo el término Aplicación móvil de Azure. Este módulo le muestra cómo crear una nueva aplicación móvil de Azure e implementar los componentes del lado del servidor para almacenar y exponer sus datos. Utilizará una base de datos SQL para almacenamiento y verá dos técnicas para crear el servicio web: Node.js y ASP.NET.

Nota: Necesitará una cuenta de Azure para completar este módulo. Consulte AZR101 para obtener detalles sobre cómo crear una cuenta. Además, para aprovechar los laboratorios basados ​​en ASP.NET, deberá estar en Windows, usar Visual Studio e instalar el SDK de Azure.

### Enlaces útiles {#helpful-links-AZR110}

- [Documentación del servicio de aplicaciones](https://docs.microsoft.com/es-es/azure/app-service/)
- [Crear una aplicación web ASP.NET Core en Azure](https://docs.microsoft.com/es-es/azure/app-service/app-service-web-get-started-dotnet)
- [Cree una aplicación web Node.js en Azure](https://docs.microsoft.com/es-es/azure/app-service/app-service-web-get-started-nodejs)
- [Cree una aplicación Xamarin.Forms con Azure](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-xamarin-forms-get-started)

### Explorando por tu cuenta {#exploring-AZR110}

- [Probar el Servicio de aplicaciones de Azure](https://azure.microsoft.com/es-es/try/app-service/)
- [Mejores prácticas para el servicio de aplicaciones de Azure](https://docs.microsoft.com/es-es/azure/app-service/app-service-best-practices)

## Construyendo un cliente de aplicación móvil de Azure (AZR115) {#building-azure-mobile-app-client}

> **Requisitos previos recomendados**: Introducción a Azure (AZR115)

Supongamos que tiene sus datos almacenados en la nube de Azure y está codificando aplicaciones Xamarin para mostrar los datos a los clientes en múltiples plataformas. Podría usar HttpClient para transferir datos codificados en JSON y un serializador para convertir entre JSON y los objetos de su modelo. Esto funciona pero es tedioso de implementar. Una opción mejor es el SDK del cliente de Azure porque simplifica las operaciones básicas de CRUD y ofrece funciones avanzadas como el almacenamiento en caché sin conexión. Este módulo le muestra cómo usar MobileServiceClient desde el SDK de Azure para trabajar con sus tablas de datos de Azure. Consumirás datos de un servicio de Azure, agregarás soporte para almacenamiento en caché y sincronización sin conexión, y administrarás conflictos de datos cuando surjan.

### Enlaces útiles {#helpful-links-AZR115}

- [Cómo usar el cliente administrado para aplicaciones móviles de Azure](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-dotnet-how-to-use-client-library)
- [Sincronización de datos sin conexión en aplicaciones móviles de Azure](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-offline-data-sync)
- [Active la sincronización sin conexión para su aplicación móvil Xamarin.Forms](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-xamarin-forms-get-started-offline-data)

## Autenticación con Azure (AZR120) {#authentication-azure}

> **Requisitos previos recomendados**: Introducción a Azure (AZR120)

Si almacena datos de clientes o negocios en Azure, deberá protegerlos de un uso no autorizado. Azure ofrece muchas opciones para autenticar usuarios y determinar a qué datos pueden acceder. Estas opciones de seguridad están deshabilitadas de forma predeterminada, lo cual es conveniente para las API públicas o de prueba; sin embargo, debe habilitarlos antes de mover su código a producción. Este módulo le muestra cómo configurar los lados del servidor y del cliente para proteger sus datos de Azure. En el servidor, habilitará la autenticación de usuario con Azure Active Directory o un proveedor externo (Google, Cuenta de Microsoft, Facebook y Twitter). En el cliente, configurará MobileServiceClient para usar OAuth y luego administrará el token de acceso para que el usuario no tenga que iniciar sesión cada vez que ejecute su aplicación.

### Enlaces útiles {#helpful-links-AZR120}

- [Autenticación y autorización en el Servicio de aplicaciones de Azure para aplicaciones móviles](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-auth)
- [Agregue autenticación a su aplicación Xamarin Forms](https://docs.microsoft.com/es-es/azure/app-service-mobile/app-service-mobile-xamarin-forms-get-started-users)
