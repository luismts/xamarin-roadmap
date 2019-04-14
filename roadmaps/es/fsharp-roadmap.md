# Introducción a F #

Esta pista proporciona una introducción al lenguaje de programación F #. Este conjunto de módulos proporciona a los desarrolladores de C # experimentados el conocimiento que necesitan para comenzar a programar en F #.

## Introducción a C # [CSC101]

Los lenguajes funcionales utilizan el principio de la inmutabilidad de los datos para evitar las variables que mantienen el estado. Esta característica hace que los programas funcionales sean más fáciles de validar y más fáciles de ejecutar en entornos de procesamiento múltiple o en paralelo. Este módulo lo introduce al lenguaje de programación funcional F #. Verá cómo codificar un programa F # simple y ejecutarlo utilizando un intérprete de línea de comandos llamado Read-Evaluate-Print-Loop (REPL).

### Enlaces útiles

- [¿Qué es F #](https://docs.microsoft.com/es-es/dotnet/fsharp/what-is-fsharp)
- [F # Tour](https://docs.microsoft.com/es-es/dotnet/fsharp/tour)
- [Comience con F # y Xamarin](https://docs.microsoft.com/xamarin/cross-platform/platform/fsharp/)
- [Obtener Visual Studio](https://visualstudio.microsoft.com/vs/)
- [Introducción a la programación con F #](https://www.youtube.com/watch?v=Teak30_pXHk&list=PLEoMzSkcN8oNiJ67Hd7oRGgD1d4YBxYGC)

### Explorando por tu cuenta

- [Guía de F #](https://docs.microsoft.com/es-es/dotnet/fsharp/)
- [Introducción a la programación funcional en F #](https://docs.microsoft.com/es-es/dotnet/fsharp/introduction-to-functional-programming/)
- [Aprenda F # a través de videos](https://docs.microsoft.com/es-es/dotnet/fsharp/#learn-f-through-videos)
- [The F # Software Foundation](https://fsharp.org/)

## Proyectos en F # [FSC102]

Para crear una aplicación F # en el mundo real, utilizará un entorno de desarrollo para crear un proyecto y organizar su código fuente en varios archivos. Querrá integrar bibliotecas de terceros y codificar sus propios tipos personalizados. Este módulo lo lleva a través de todo el proceso de usar Visual Studio para crear y ejecutar una aplicación de consola F #.

### Enlaces útiles

- [Comience con F # en Visual Studio](https://docs.microsoft.com/es-es/dotnet/fsharp/get-started/get-started-visual-studio)
- [Comience con F # en Visual Studio para Mac](https://docs.microsoft.com/es-es/dotnet/fsharp/get-started/get-started-with-visual-studio-for-mac)
- [Comience con F # en Visual Studio Code](https://docs.microsoft.com/es-es/dotnet/fsharp/get-started/get-started-vscode)

### Explorando por tu cuenta

- [Guía de estilo F #](https://docs.microsoft.com/es-es/dotnet/fsharp/style-guide/)

> Prerrequisitos recomendados: Introducción a F # [FSC101].

## Estructuras de datos en F # [FSC103]

La administración de datos en memoria es necesaria en la mayoría de las aplicaciones y F # contiene poderosas API de procesamiento y almacenamiento de datos para ayudarlo. Las API están optimizadas para casos de uso específicos; por ejemplo, algunos funcionan mejor si sus datos son estáticos, mientras que otros están destinados a grandes conjuntos de datos. Este módulo le muestra varias estructuras de datos comunes de F # y analiza las ventajas y desventajas de cada uno. Al final del módulo, podrá elegir la opción de almacenamiento adecuada para su aplicación.

### Enlaces útiles

- [Elegir entre funciones de recopilación](https://fsharpforfunandprofit.com/posts/list-module-functions/)

### Explorando por tu cuenta

- [Tipos de colección F #](https://docs.microsoft.com/es-es/dotnet/fsharp/language-reference/fsharp-collection-types)
- [Qué tipos de uso](https://docs.microsoft.com/es-es/dotnet/fsharp/tour#which-types-to-use)

> Prerrequisitos recomendados: Proyectos en F # [FSC102].

## Usando Async [FSC104]

Las aplicaciones a menudo necesitan realizar operaciones de larga duración, como descargar datos de la nube o acceder al sistema de archivos local. Las bibliotecas que realizan este trabajo por usted generalmente ofrecen API asíncronas que permiten que su aplicación responda a las sugerencias de los usuarios mientras estas operaciones se ejecutan en segundo plano. Este módulo le muestra cómo usar la palabra clave asíncrona para escribir este tipo de código asíncrono. También verá los detalles de la implementación subyacente y analizará algunas de las mejores prácticas a seguir al utilizar esta función de C #.

### Enlaces útiles

- [Programación asíncrona en F #](https://docs.microsoft.com/es-es/dotnet/fsharp/tutorials/asynchronous-and-concurrent-programming/async)
- [Flujos de trabajo asíncronos](https://docs.microsoft.com/es-es/dotnet/fsharp/language-reference/asynchronous-workflows)

### Explorando por tu cuenta

- [Flujos de trabajo asíncronos](https://docs.microsoft.com/es-es/dotnet/fsharp/language-reference/asynchronous-workflows)
- [Información y consejos importantes](https://docs.microsoft.com/es-es/dotnet/fsharp/tutorials/asynchronous-and-concurrent-programming/async#important-info-and-advice)


> Prerrequisitos recomendados: Estructuras de datos en F # [FSC103]

## Aplicación parcial y coincidencia de patrones [FSC105]

Una de las fortalezas de los lenguajes funcionales es su capacidad para combinar funciones de manera concisa pero poderosa. Por ejemplo, puede pasar una función como parámetro a otra función o adaptar una función general a sus necesidades específicas mediante la codificación de algunos de los valores de los parámetros. Este módulo le muestra cómo usar la aplicación de curry y función parcial para crear nuevas funciones que realicen la operación exacta que necesita. Otra característica útil en muchos idiomas funcionales es la coincidencia de patrones que le permite examinar los valores de los datos y la rama en función de alguna característica coincidente de los datos. En este módulo, utilizará la coincidencia de patrones para seleccionar datos de una colección y aplicar una función para transformarlos.

### Enlaces útiles

- [Coincidencia de patrones](https://docs.microsoft.com/es-es/dotnet/fsharp/language-reference/pattern-matching)


### Explorando por tu cuenta

- [Expresiones de coincidencia](https://docs.microsoft.com/es-es/dotnet/fsharp/language-reference/match-expressions)

> Prerrequisitos recomendados: Estructuras de datos en F # [FSC103].

## Proveedores de tipo en F # [FSC106]

F # facilita la carga de datos externos en su aplicación. Un proveedor de tipo F # encapsula todas las operaciones necesarias: se conecta al origen de datos, determina la forma de los datos, construye objetos y llena los objetos con los datos externos. Este módulo le muestra cómo usar los Proveedores de Tipo en su aplicación. Verá cómo crear una instancia de un proveedor, leer datos y ejecutar consultas contra el proveedor para seleccionar solo los datos que necesita.

### Enlaces útiles

- [Proveedores de tipos](https://docs.microsoft.com/es-es/dotnet/fsharp/tutorials/type-providers/)
- [Tutorial: Crear un proveedor de tipos](https://docs.microsoft.com/es-es/dotnet/fsharp/tutorials/type-providers/creating-a-type-provider)

### Explorando por tu cuenta

- [El SDK del proveedor de tipos F #](https://github.com/fsprojects/FSharp.TypeProviders.SDK)

> Prerrequisitos recomendados: Proveedores de tipo en F # [FSC105].
