# Xamarin.Forms {#xamarinforms}

Xamarin.Forms es perfecto para aplicaciones multiplataforma que muestran "formularios sobre datos" donde el objetivo principal de la aplicación es mostrar datos de manera estandarizada. Esta pista se centra en la creación de aplicaciones Xamarin.Forms dirigidas a iOS, Android y Windows.

## Introducción a Xamarin.Forms (XAM120) {# introduction-xamarinforms}

> **Requisitos previos recomendados**: Introducción al desarrollo móvil multiplataforma (XAM110)

Xamarin.Forms le permite definir una única interfaz de usuario que comparte en todas sus plataformas compatibles. Esto maximiza su capacidad para compartir código: puede compartir su UI y su lógica empresarial. En este curso, creará una nueva aplicación Xamarin.Forms y definirá su IU compartida en el código. También verá cómo acceder a las características específicas de la plataforma, como el marcador del teléfono o la cámara, que no tienen un modelo de programación compartido integrado en Xamarin.Forms.

- Aprende la estructura básica de una aplicación móvil Xamarin.Forms
- Definir una interfaz de usuario compartida para Android y iOS
- Implementar una aplicación desde Visual Studio a Android y / o iOS

### Enlaces útiles

- [Cree su primera aplicación Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/get-started/first-app/index)
- [Crear una aplicación Xamarin.Forms de una sola página](https://docs.microsoft.com/es-es/xamarin/get-started/quickstarts/single-page)

### Explorando por tu cuenta

- [Fundamentos de la aplicación Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/)
- [Vistas de la interfaz de usuario de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/index)


## XAML en Xamarin.Forms (XAM130) {# xaml-xamarinforms}

> **Prerrequisitos recomendados**: Introducción a Xamarin.Forms (XAM120)

Xamarin.Forms le permite definir su interfaz de usuario utilizando el lenguaje de marcado de aplicaciones extensible (XAML). Esto le proporciona una separación clara entre la interfaz de usuario y el comportamiento y facilita el uso de un experto en diseño y herramientas de diseño. Este curso le muestra cómo definir su UI en XAML. Creará páginas y agregará controles, todo en el marcado. También verá cómo acceder a los elementos de la IU desde el código para poder suscribirse a eventos de la IU y actualizar las propiedades de la IU a medida que cambian sus datos.

- Cree la interfaz de usuario y agregue controles para una aplicación Xamarin.Forms utilizando XAML
- Acceda a los elementos de la interfaz de usuario basados ​​en XAML desde el código
- Suscribirse a eventos de interfaz de usuario basados ​​en XAML

### Enlaces útiles

- [eXtensible Application Markup Language (XAML)](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/index)
- [Xamarin.Forms XAML Basics](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/xaml-basics/)

### Explorando por tu cuenta

- [XAML Previewer for Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/xaml-previewer/)
- [Extensiones de marcado XAML](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/markup-extensions/)

## Diseño en Xamarin.Forms (XAM135) {# layout-xamarinforms}

> **Prerrequisitos recomendados**: XAML en Xamarin.Forms (XAM130)

Las aplicaciones Xamarin.Forms se ejecutan en una amplia gama de dispositivos con diferentes tamaños de pantalla y densidades de píxeles. Es un desafío crear una IU que se vea bien y se comporte correctamente en todos los casos. Xamarin.Forms ayuda a resolver este problema al proporcionar contenedores de diseño flexibles que pueden calcular el tamaño y la posición de sus controles de UI automáticamente; incluso se recalculan si el usuario gira el dispositivo o cambia el tamaño de la ventana de la aplicación. Este curso contiene información detallada sobre StackLayout y Grid, los dos contenedores de diseño más populares en Xamarin.Forms. También le muestra cómo agregar el desplazamiento cuando su UI es demasiado grande para el área de pantalla disponible.

- Visualizar vistas en una lista vertical u horizontal usando StackLayout
- Visualizar vistas en filas y columnas usando Grid

### Enlaces útiles

- [Controles XAML](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/xaml-controls)
- [Diseños de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/controls/layouts)

### Explorando por tu cuenta

- [Clase StackLayout](https://docs.microsoft.com/es-es/dotnet/api/xamarin.forms.stacklayout?view=xamarin-forms)
- [Clase de cuadrícula](https://docs.microsoft.com/es-es/dotnet/api/xamarin.forms.grid?view=xamarin-forms)

## Recursos y estilos en Xamarin.Forms (XAM140) {# resources-styles-xamarinforms}

> **Prerrequisitos recomendados**: XAML en Xamarin.Forms (XAM130)

El uso de las mismas fuentes y colores en toda su interfaz de usuario crea una apariencia y sensación consistentes. Xamarin.Forms proporciona una manera de definir estos valores en un solo lugar y buscarlos en todos los lugares donde se utilizan; esto garantiza la coherencia en toda la aplicación y simplifica las actualizaciones. Este curso le muestra cómo definir y aplicar un recurso tanto en código como en XAML. También le muestra cómo agrupar varias configuraciones en un estilo para que pueda aplicarlas todas a la vez.

- Crear una interfaz de usuario consistente usando recursos y estilos
- Aplicar las opciones de accesibilidad del usuario con los estilos incorporados.

### Enlaces útiles

- [Diseñar aplicaciones de Xamarin.Forms con estilos XAML](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/styles/xaml/index)
- [Diseñar aplicaciones Xamarin.Forms utilizando hojas de estilo en cascada (CSS)](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/styles/css/index)

### Explorando por tu cuenta

- [Styling Xamarin.Forms Apps](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/styles/)

## Patrones de navegación en Xamarin.Forms (XAM205) {# navigation-patterns-xamarinforms}

> **Prerrequisitos recomendados**: Diseño en Xamarin.Forms (XAM135)

Parte de la planificación de la arquitectura de su aplicación es decidir cómo se moverá el usuario entre las páginas. ¿Los usuarios necesitarán avanzar o retroceder más a través de una secuencia de páginas? ¿Su aplicación tiene una página de inicio o hay varias páginas de nivel superior que son todas importantes? Su elección de navegación debería funcionar bien con el contenido de su aplicación y sentirse nativo a cada plataforma que elija. Este curso le muestra cómo codificar dos patrones de navegación comunes: apilar y tabular. Incluye pautas para ayudarle a decidir qué patrón es el adecuado para su aplicación. El curso también cubre cómo la infraestructura de navegación se adapta automáticamente a la plataforma de tiempo de ejecución y le muestra cómo personalizar el comportamiento cuando sea necesario.

- Elija entre la pila y la navegación de pestañas para su aplicación
- Implementar pila y navegación de pestañas.
- Mostrar contenido transitorio utilizando páginas modales.

### Enlaces útiles

- [Navegación jerárquica](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/navigation/hierarchical)
- [Página tabulada de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/navigation/tabbed-page)
- [Páginas modales de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/navigation/modal)

### Explorando por tu cuenta

- [Xamarin.Forms Navigation](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/navigation/)

## Enlace de datos en Xamarin.Forms (XAM270) {# data-binding-xamarinforms}

> **Prerrequisitos recomendados**: XAML en Xamarin.Forms (XAM130)

La mayoría de las aplicaciones necesitan cargar datos de código subyacente en su interfaz de usuario y transferir los datos ingresados ​​por el usuario a sus modelos de código subyacente. El enlace de datos ofrece una forma limpia de realizar ambas tareas. El enlace de datos utiliza objetos de enlace que unen dos propiedades y mantienen sus valores sincronizados a medida que cambian. Este curso le muestra cómo crear enlaces tanto en código como en XAML. También verá cómo implementar convertidores de valor para usar cuando los tipos de las dos propiedades son diferentes.

- Sincronizar datos entre su UI y el código subyacente mediante enlaces
- Minimice el acoplamiento entre su UI y el código subyacente para permitir cambios sencillos en la UI

### Enlaces útiles

- [Fundamentos de vinculación de datos](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/xaml-basics/data-binding-basics)

## Usando ListView en Xamarin.Forms (XAM280) {# listview-xamarinforms}

> **Prerrequisitos recomendados**: Enlace de datos en Xamarin.Forms (XAM270)

La mayoría de las aplicaciones necesitan presentar recopilaciones de datos en su interfaz de usuario. En este curso, agregará un Xamarin.Forms ListView a su aplicación, lo llenará con una colección de objetos de datos y manejará la selección de elementos. También utilizará las plantillas de celdas integradas para personalizar ligeramente la apariencia de cada fila. Finalmente, implementará dos patrones comunes de experiencia de usuario: acciones de extracción y de contexto.

ListView tiene una selección limitada de estilos de celda incorporados. Estas celdas estándar manejan casos comunes y usted debe usarlas si satisfacen sus necesidades. De lo contrario, puede crear una celda personalizada que representará de forma única sus datos y se corresponderá con el aspecto general de su aplicación. Este curso le muestra cómo definir una plantilla de fila, cómo agregar encabezados / pies de página y cómo mostrar datos agrupados. También examinará varias estrategias de ajuste de rendimiento, incluido el almacenamiento en caché de células.

- Crea una vista de lista y rellénala con elementos
- Responder cuando el usuario interactúa con ListView.
- Personalice la apariencia de una fila de ListView usando tipos de celda incorporados
- Crear diseños de celdas personalizados para un ListView
- Usar múltiples diseños de celdas en un solo ListView
- Agrupar celdas en secciones.

### Enlaces útiles

- [Xamarin.Forms ListView](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/)
- [Fuentes de datos de ListView](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/data-and-databinding)
- [Personalizando la apariencia de la celda ListView](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/customizing-cell-appearance)
- [Personalizando la apariencia de ListView](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/customizing-list-appearance)
- [ListView Interactivity](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/interactivity)

### Explorando por tu cuenta

- [ListView Performance](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/user-interface/listview/performance)

## Navegación de detalles maestros y cajones (XAM290) {# master-detail-and-drawer-navigation}

> **Prerrequisitos recomendados**: enlace de datos en Xamarin.Forms (XAM270), usando ListView en Xamarin.Forms (XAM280), patrones de navegación en Xamarin.Forms (XAM205)

Crear una gran aplicación significa crear una ruta de navegación clara a través de su contenido. A medida que su aplicación crece en complejidad, debe proporcionar una estructura de interfaz de usuario que permita a los usuarios cambiar rápidamente entre varias pantallas. En este curso, explorarás dos técnicas de UI usando una relación maestro-detalle. Aprenderá a cambiar entre varias páginas de contenido utilizando la navegación de cajón, y creará una verdadera interfaz de usuario con detalles maestros que permite a los usuarios explorar una gran colección de datos mientras aprovechan el espacio de pantalla disponible. Este curso incluye una mirada en profundidad a la MasterDetailPage de Xamarin.Forms y le muestra las mejores prácticas de coordinación entre las páginas maestra y de detalles.

- Elija entre dividir y desplegar para su vista maestra
- Alternar entre páginas con la navegación emergente del cajón
- Mostrar una colección usando la vista dividida de detalles maestros

### Enlaces útiles

- [Página de detalles maestros de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/navigation/master-detail-page)

### Explorando por tu cuenta

- [Clase MasterDetailPage](https://docs.microsoft.com/es-es/dotnet/api/xamarin.forms.masterdetailpage?view=xamarin-forms#applies-to)

## Diseñe un MVVM ViewModel en Xamarin.Forms (XAM320) {# mvvm-xamarinforms}

> **Prerrequisitos recomendados**: Enlace de datos en Xamarin.Forms (XAM270), usando ListView en Xamarin.Forms (XAM280), XAML en Xamarin.Forms (XAM130), Arquitectura de aplicación móvil (XAM301)

Nos centraremos en cómo diseñar adecuadamente su aplicación para separar la _presentación_ de la lógica de negocios y los datos que la impulsan. Veremos tres patrones principales que son populares en el mundo móvil: Model-View-Controller (MVC), Model-View-Presenter (MVP), y Model-View-ViewModel (MVVM).

- Identificar cuándo usar el patrón Model-View-ViewModel
- Use un modelo de visualización para impulsar el comportamiento visual.
- Mejora de la capacidad de prueba del código a través de propiedades vinculables a datos

### Enlaces útiles

- [Xamarin.Forms MVVM](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/xaml/xaml-basics/data-bindings-to-mvvm)

## Efectos de Xamarin.Forms (XAM330) {# effects-xamarinforms}

> **Prerrequisitos recomendados**: Enlace de datos en Xamarin.Forms (XAM270)

Los elementos de la interfaz de usuario de Xamarin.Forms son objetos modelo que se convierten en controles de plataforma nativos en tiempo de ejecución. Para aprovechar al máximo el estilo y los patrones únicos de cada plataforma, puede trabajar directamente con los controles nativos en lugar de con los elementos de Xamarin.Forms. Este curso le muestra cómo usar Effects para acceder y personalizar los controles nativos de pares. Esto le da el mismo poder para modificar la apariencia de su interfaz de usuario como un desarrollador nativo.

- Aplica un efecto en Xamarin. Formas
- Crear un efecto para personalizar el comportamiento.
- Añadir opciones de configuración a un efecto.

### Enlaces útiles

- [Introducción a los efectos](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/effects/)
- [Creando un efecto](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/effects/creating)

### Explorando por tu cuenta

- [Efectos de Xamarin.Forms](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/effects/)

## Representantes de Xamarin.Forms (XAM335) {# renderers-xamarinforms}

> **Prerrequisitos recomendados**: Efectos de Xamarin.Forms (XAM330)

¿Qué sucede si su aplicación Xamarin.Forms necesita mostrar un gráfico interactivo, una superficie de dibujo o un selector de color? Xamarin.Forms le permite ampliar el conjunto de elementos de la interfaz de usuario existentes al escribir su propio control personalizado para manejar estos casos. En este curso, verá cómo usar un Renderer para implementar la interfaz de usuario y el comportamiento para un control totalmente personalizado. Además, utilizará un Renderer para modificar el comportamiento de un control existente para satisfacer las necesidades específicas de su aplicación.

- Modificar un renderizador de control existente
- Crear un nuevo control con un nuevo renderizador.
- Enviar notificaciones entre un elemento Xamarin.Forms y controles nativos

### Enlaces útiles

- [Introducción a los renderizadores personalizados](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/custom-renderer/introduction)
- [Clases base del renderizador y controles nativos](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/custom-renderer/renderers)

### Explorando por tu cuenta

- [Xamarin.Forms Custom Renderers](https://docs.microsoft.com/es-es/xamarin/xamarin-forms/app-fundamentals/custom-renderer/)
