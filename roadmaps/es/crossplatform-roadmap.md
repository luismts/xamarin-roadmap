# Xamarin Diseño multiplataforma {#xamarin-diseño-multiplataforma}

Aprenda conceptos y API que se pueden utilizar en las plataformas móviles dominantes (iOS, Android y Windows). La mayoría de los módulos en esta guia utilizan Xamarin.Forms, pero los conceptos también pueden aplicarse al desarrollo nativo.

## Introducción a Xamarin (XAM101) {#introduccion-xamarin}

¿Qué es Xamarin? ¿En qué se diferencian Xamarin.Forms de Xamarin.Android y Xamarin.iOS? ¿Qué código puedo compartir en mis aplicaciones? ¿Puedo desarrollar en Windows y macOS? Este módulo responde a estas preguntas y más. Al final del módulo, podrá elegir el enfoque de Xamarin que sea adecuado para usted. También configurará su máquina de desarrollo y ejecutará una aplicación en Windows, el simulador de iOS y un emulador de Android

- Describa el ciclo de vida de desarrollo de software móvil (SDLC) con Xamarin
- Instalar las herramientas de Xamarin para Visual Studio.
- Mantenga sus herramientas de desarrollo al día.
- Compilar aplicaciones móviles con Visual Studio en macOS y / o Windows

### Enlaces útiles

- [Obtener Visual Studio](https://visualstudio.microsoft.com/vs/)
- [Herramientas de desarrollo de Xamarin](https://visualstudio.microsoft.com/xamarin/)
- [Xamarin Profiler](https://docs.microsoft.com/en-us/xamarin/tools/profiler/)
- [Visual Studio App Center](https://visualstudio.microsoft.com/app-center/)

### Explorando por tu cuenta

- [Introducción al desarrollo móvil](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/introduction-to-mobile-development)
- [Introducción al ciclo de vida del desarrollo de software móvil](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/introduction-to-mobile-sdlc)
- [Mantenerse actualizado con el desarrollo de Xamarin (blog)](https://devblogs.microsoft.com/xamarin/)

## Introducción al desarrollo móvil multiplataforma (XAM110) {#introduccion-desarrollo-movil-multiplataforma}

> **Prerrequisitos recomendados**: Introducción a Xamarin (XAM101), Introducción a Xamarin.Android, Introducción a Xamarin.iOS

Una de las ventajas de usar Xamarin sobre el enfoque tradicional de plataforma específica es el nivel de uso compartido de código que puede alcanzar en iOS, Android y Windows. En esta clase, exploraremos formas de estructurar su código compartido utilizando las bibliotecas de clases portátiles, las bibliotecas estándar de .NET y los proyectos de activos compartidos. Analizaremos las ventajas y desventajas de cada enfoque y veremos cómo acceder a las características específicas de la plataforma en cada modelo.

- Trabajar con paquetes compartidos desde NuGet
- Usa proyectos compartidos para compartir código entre plataformas
- Usa las bibliotecas de clases portátiles para compartir código entre plataformas
- Compartir código utilizando bibliotecas estándar .NET

### Enlaces útiles

- [Una introducción a NuGet](https://docs.microsoft.com/en-us/nuget/what-is-nuget)
- [Compartir código compartido de proyectos](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/shared-projects)
- [.NET Standard](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)

### Explorando por tu cuenta

- [Creación de aplicaciones multiplataforma](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/building-cross-platform-applications/)
- [Opciones de código compartido](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/code-sharing)
- [Acceso a datos multiplataforma](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/)
- [Servicios web multiplataforma](https://docs.microsoft.com/en-us/xamarin/cross-platform/data-cloud/web-services/)
- [#if (Referencia de C #)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/preprocessor-directives/preprocessor-if)

## Consumir servicios web basados en REST (XAM150) {#consumir-servicios-web-rest}

> **Prerrequisitos recomendados**: Introducción a Xamarin.Forms

Los usuarios esperan acceder a su información en cualquier momento desde cualquier ubicación usando cualquier dispositivo. Esto lleva a la mayoría de los desarrolladores de aplicaciones a almacenar datos en la nube y recuperarlos según sea necesario desde los dispositivos cliente. Los servicios web basados ​​en REST son la estrategia dominante para este tipo de comunicación de dispositivo a servidor. En este módulo, verá cómo consumir servicios web basados ​​en REST con HttpClient utilizando la pila de red administrada y los controladores específicos de la plataforma que aumentan el rendimiento. También aprenderá algunas estrategias comunes para enfrentar los desafíos únicos que enfrentan los dispositivos móviles cuando se comunican a través de la red.

- Obtener las capacidades de red del dispositivo.
- Describir los puntos fuertes del uso de servicios basados en REST.
- Consumir servicios REST en aplicaciones basadas en Xamarin.
- Aprovechar las pilas de redes específicas de la plataforma

### Enlaces útiles

- [Introducción a los servicios web](https://docs.microsoft.com/en-us/xamarin/cross-platform/data-cloud/web-services/)
- [Llamar a una API REST desde un cliente .NET](https://docs.microsoft.com/en-us/aspnet/web-api/overview/advanced/calling-a-web-api-from-a-net -cliente)
- [Clase HttpClient](https://docs.microsoft.com/en-us/dotnet/api/system.net.http.httpclient)
- [Xamarin.Essentials: Conectividad](https://docs.microsoft.com/en-us/xamarin/essentials/connectivity?tabs=android)

### Explorando por tu cuenta

- [Ejemplo de TodoREST](https://developer.xamarin.com/samples/xamarin-forms/WebServices/TodoREST/)
- [Xamarin.Essentials](https://docs.microsoft.com/en-us/xamarin/essentials/?context=xamarin/)

## SQLite y datos móviles (XAM160) {#sqlite-datos-móviles}

> **Prerrequisitos recomendados**: Introducción a Xamarin.Forms

Muchas aplicaciones necesitan almacenar datos localmente en el dispositivo para que estén disponibles incluso cuando el acceso a la red no es confiable. Las preferencias del usuario, los archivos de datos y los datos relacionales pueden caer en esta categoría. Este módulo comienza con una encuesta de las opciones de almacenamiento local disponibles para usted en sus aplicaciones Xamarin. Luego se concentra en almacenar datos relacionales usando una base de datos SQLite. Al final del módulo, habrá visto cómo identificar la ubicación correcta para su archivo de base de datos y cómo insertar, actualizar, recuperar y eliminar datos de manera eficiente mediante llamadas asíncronas de E / S.

- Comprender las opciones de almacenamiento de datos disponibles.
- Crear, insertar, actualizar y eliminar registros con SQLite
- Trabajar con SQLite de forma asíncrona.

### Enlaces útiles

- [Bases de datos locales de Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/databases)
- [Almacenar datos en una base de datos local SQLite.NET](https://docs.microsoft.com/en-us/xamarin/get-started/quickstarts/database)
- [Tutorial de la base de datos local de Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/get-started/tutorials/local-database/)
- [Manejo de archivos en Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/files)

## Preparando para publicar su aplicación (XAM220) {#preparando-para-publicar-su-aplicación}

> **Requisitos previos recomendados**: Introducción a Xamarin (XAM101)

El objetivo para la mayoría de los desarrolladores es llevar sus aplicaciones a las distintas tiendas y luego a los dispositivos de los clientes. Hay muchos pasos entre el momento en que su aplicación se completa con el código y cuando está lista para enviar las tiendas. Este módulo le muestra cómo prepararse para la publicación, independientemente de las plataformas que admita o la tienda que desee utilizar. Incluye consejos para hacer que su aplicación se vea bien, instrucciones sobre cómo usar el enlazador para reducir el tamaño de su aplicación y algunas orientaciones sobre cómo seleccionar una tienda.

La mecánica del mercado / tienda de cada plataforma no está cubierta en este módulo. Para aprender cómo empaquetar y cargar su aplicación en la tienda de aplicaciones iOS, Google Play Store o Windows Marketplace, le recomendamos que vea uno de los videos específicos relacionados con la publicación en esas tiendas.

- Prepare su aplicación para la publicación.
- Use el enlazador para reducir el tamaño de su paquete final de aplicaciones
- Conservar código crítico al vincular su aplicación
- Publica tu aplicación

### Enlaces útiles

- [Publicar una aplicación de Android](https://docs.microsoft.com/en-us/xamarin/android/deploy-test/publishing/)
- [Publicación en la tienda de aplicaciones](https://docs.microsoft.com/en-us/xamarin/mac/deploy-test/publishing-to-the-app-store/)

### Explorando por tu cuenta

#### Android
- [Enlace](https://docs.microsoft.com/en-us/xamarin/android/deploy-test/linker)
- [Firma de la aplicación](https://source.android.com/security/apksigning/)
- [Licencia de aplicación de Google](https://developer.android.com/guide/google/play/licensing/index.html)

#### iOS
- [ID de desarrollador y GateKeeper](https://developer.apple.com/resources/developer-id/)

## Patrones para el desarrollo móvil multiplataforma (XAM250) {#patrones-para-el-desarrollo-móvil-multiplataforma}

> **Requisitos previos recomendados**: Introducción al desarrollo móvil multiplataforma (XAM110)

A veces, necesita acceder a API específicas de la plataforma que no están intrínsecamente disponibles desde su código compartido. Por ejemplo, es posible que desee tomar una imagen, realizar una E / S de archivo o reproducir audio. El enfoque recomendado es codificar una capa de abstracción que le permita invocar la API específica de la plataforma desde un código compartido. Este módulo le muestra tres técnicas para hacer esto: patrón de fábrica, patrón de localizador de servicio e inyección de dependencia.

- Localizar dependencias utilizando el patrón de fábrica.
- Utilice un Localizador de servicios para registrar y recuperar dependencias
- Use un contenedor IoC para inyectar dependencias automáticamente

### Enlaces útiles

- [Explorando el patrón de diseño de fábrica](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee817667(v=pandp.10))
- [Inyección de dependencia](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/dependency-injection)
- [Introducción a DependencyService](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/dependency-service/introduction)

### Explorando por tu cuenta

- [Resolución de dependencia en Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/internals/dependency-resolution#injecting-a-dependency-resolution-method)

## Arquitectura de aplicación móvil (XAM301) {#arquitectura-aplicación-móvil}

> **Requisitos previos recomendados**: Introducción al desarrollo móvil multiplataforma (XAM110)

Se centrará en cómo diseñar adecuadamente su aplicación para separar la presentación de la lógica de negocios y los datos que la impulsan. Verá tres patrones principales que son populares en el mundo móvil: Model-View-Controller (MVC), Model-View-Presenter (MVP), y Model-View-ViewModel (MVVM).

- Aplicar Model-View-Controller a una aplicación Xamarin.iOS
- Aplicar Model-View-Presenter a una aplicación Xamarin.Android
- Aplicar Model-View-ViewModel a una aplicación Xamarin.Forms

### Enlaces útiles

- [Arquitectura](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/building-cross-platform-applications/architecture)
- [El modelo Model-View-ViewModel Pattern](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/mvvm)
- [Resumen MVVM](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/creating-mobile-apps-xamarin-forms/summaries/chapter18)

### Explorando por tu cuenta

- [Patrones de aplicación empresarial utilizando el libro electrónico Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/)

## Diagnóstico de problemas de administración de memoria (XAM370) {#diagnóstico-problemas-administración-memoria}

Hay dos áreas conceptuales de memoria en una aplicación Xamarin: la memoria administrada en el tiempo de ejecución de Mono y el espacio de memoria utilizado para los objetos nativos. Los objetos estándar .NET / Mono se asignan en el lado administrado, mientras que los tipos como los elementos de la interfaz de usuario tienen una representación en ambas áreas. Esto significa que hay varios casos a considerar cuando se soluciona el problema del uso de la memoria de su aplicación. Este módulo comienza mostrándole cómo suceden las pérdidas de memoria en la memoria administrada, incluso con un recolector de basura sofisticado y cómo descubrirlas y solucionarlas. A continuación, muestra varios problemas de memoria que son específicos de Xamarin.iOS y Xamarin.Android.

- Identifique y corrija las fugas de memoria en su código.
- Reconocer y solucionar problemas de memoria específicos de Xamarin.iOS
- Reconocer y solucionar problemas de memoria específicos de Xamarin.Android.

### Enlaces útiles

- [Recolección de basura](https://docs.microsoft.com/en-us/xamarin/android/internals/garbage-collection)
- [Implementación de un método Dispose](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/implementing-dispose)


### Explorando por tu cuenta

- [Rendimiento multiplataforma](https://docs.microsoft.com/en-us/xamarin/cross-platform/deploy-test/memory-perf-best-practices)
- [Xamarin Profiler](https://docs.microsoft.com/en-us/xamarin/tools/profiler/)
