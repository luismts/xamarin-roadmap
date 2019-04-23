# Xamarin Cross-platform Design

Learn concepts and APIs which are usable across the dominant mobile platforms (iOS, Android, and Windows). Most modules in this track use Xamarin.Forms, but the concepts can also be applied to native development.

## Getting Started with Xamarin (XAM101)

What is Xamarin? How does Xamarin.Forms differ from Xamarin.Android and Xamarin.iOS? What code can I share across my apps? Can I develop on Windows and macOS? This module answers these questions and more. By the end of the module, you will be able to choose the Xamarin approach that is right for you. You will also set up your development machine and run an app on Windows, the iOS simulator, and an Android emulator. 

- Describe the mobile Software Development Lifecycle (SDLC) with Xamarin
- Install the Xamarin tools for Visual Studio
- Keep your development tools up to date
- Compile mobile applications with Visual Studio on macOS and/or Windows

### Useful links

-	[Get Visual Studio](https://visualstudio.microsoft.com/vs/) 
- [Xamarin Development Tools](https://visualstudio.microsoft.com/xamarin/)
- [Xamarin Profiler](https://docs.microsoft.com/en-us/xamarin/tools/profiler/)
- [Visual Studio App Center](https://visualstudio.microsoft.com/app-center/)

### Exploring on your own

- [Introduction to Mobile Development](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/introduction-to-mobile-development)
- [Introduction to the Mobile Software Development Lifecycle](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/introduction-to-mobile-sdlc)
- [Staying up to date with Xamarin development (blog)](https://devblogs.microsoft.com/xamarin/)

## Introduction to Cross-Platform Mobile Development (XAM110)

> **Recommended Prerequisites**:  Getting Started with Xamarin (XAM101), Introduction to Xamarin.Android, Introduction to Xamarin.iOS 

One of the advantages to using Xamarin over the traditional platform-specific approach is the level of code-sharing you can achieve across iOS, Android, and Windows. In this class, we will explore ways to structure your shared code using Portable Class Libraries, .NET Standard libraries, and Shared Asset Projects. We will look at the pros and cons of each approach and see how to access platform-specific features in each model.

- Work with shared packages from NuGet
- Use Shared Projects to share code between platforms
- Use Portable Class Libraries to share code between platforms
- Share code using .NET Standard libraries

### Useful links

- [An introduction to NuGet](https://docs.microsoft.com/en-us/nuget/what-is-nuget)
- [Shared Projects code sharing](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/shared-projects)
- [.NET Standard](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)

### Exploring on your own

-	[Building Cross Platform Applications](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/building-cross-platform-applications/)
- [Sharing Code Options](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/code-sharing)
- [Cross-Platform Data Access](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/)
- [Cross-Platform Web Services](https://docs.microsoft.com/en-us/xamarin/cross-platform/data-cloud/web-services/)
- [#if (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/preprocessor-directives/preprocessor-if)

## Consuming REST-based Web Services (XAM150)

> **Recommended Prerequisites**:  Introduction to Xamarin.Forms

Users expect to access their information anytime from any location using any device. This leads most app developers to store data in the cloud and retrieve it as needed from client devices. REST-based web services are the dominant strategy for this type of device-to-server communication. In this module, you will see how to consume REST-based web services with HttpClient using both the managed networking stack and the platform-specific handlers that boost performance. You will also learn some common strategies for dealing with the unique challenges that mobile devices face when communicating over the network.

- Obtain the device's network capabilities
- Describe the strengths of using REST-based services
- Consume REST services in Xamarin-based applications
- Leverage the platform-specific networking stacks

### Useful links

- [Introduction to Web Services](https://docs.microsoft.com/en-us/xamarin/cross-platform/data-cloud/web-services/) 
- [Calling a REST API From a .NET Client](https://docs.microsoft.com/en-us/aspnet/web-api/overview/advanced/calling-a-web-api-from-a-net-client) 
-	[HttpClient Class ](https://docs.microsoft.com/en-us/dotnet/api/system.net.http.httpclient) 
- [Xamarin.Essentials: Connectivity](https://docs.microsoft.com/en-us/xamarin/essentials/connectivity?tabs=android)


### Exploring on your own

-	[TodoREST Sample](https://developer.xamarin.com/samples/xamarin-forms/WebServices/TodoREST/) 
- [Xamarin.Essentials](https://docs.microsoft.com/en-us/xamarin/essentials/?context=xamarin/)

## SQLite and Mobile Data (XAM160)

> **Recommended Prerequisites**:  Introduction to Xamarin.Forms

Many apps need to store data locally on the device so it is available even when network access is unreliable. User preferences, data files, and relational data can all fall into this category. This module starts with a survey of the local-storage options available to you in your Xamarin applications. It then concentrates on storing relational data using a SQLite database. By the end of the module, you will have seen how to identify the proper location for your database file and how to insert, update, retrieve, and delete data efficiently using asynchronous I/O calls.

- Understand the available data storage options
- Create, Insert, Update, and Delete records with SQLite
- Work with SQLite asynchronously

### Useful links

-	[Xamarin.Forms Local Databases](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/databases) 
- [Store Data in a Local SQLite.NET Database](https://docs.microsoft.com/en-us/xamarin/get-started/quickstarts/database)
- [Xamarin.Forms Local Database Tutorial](https://docs.microsoft.com/en-us/xamarin/get-started/tutorials/local-database/)
- [File Handling in Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/files)

## Preparing to publish your application (XAM220)

> **Recommended Prerequisites**:  Getting Started with Xamarin (XAM101)

The goal for most developers is to get their apps into the various stores and then onto customer devices. There are many steps between the time your app is code-complete and when it is ready for submission the stores. This module shows you how to prepare for publishing regardless of which platforms you support or the store you intend to use. It includes advice for making your app look good, instructions on using the linker to reduce the size of your app, and some guidance on selecting a store.

The mechanics of each platform's marketplace/store are not covered in this module. To learn how to package and upload your app to the iOS App Store, Google Play Store, or Windows Marketplace we recommend you watch one of the specific videos related to publishing in those stores. 

- Prepare your app for publishing
- Use the linker to reduce the size of your final app package
- Preserve critical code when linking your app
- Publish your app

### Useful links

-	[Publishing an Android Application](https://docs.microsoft.com/en-us/xamarin/android/deploy-test/publishing/) 
- [Publishing on App Store](https://docs.microsoft.com/en-us/xamarin/mac/deploy-test/publishing-to-the-app-store/)

### Exploring on your own

#### Android
-	[Linking](https://docs.microsoft.com/en-us/xamarin/android/deploy-test/linker) 
- [Application Signing](https://source.android.com/security/apksigning/)
- [Google Application Licensing](https://developer.android.com/guide/google/play/licensing/index.html)

#### iOS
- [Developer ID and GateKeeper](https://developer.apple.com/resources/developer-id/)

## Patterns for Cross Platform Mobile Development (XAM250)

> **Recommended Prerequisites**:  Introduction to Cross-Platform Mobile Development (XAM110)

Sometimes you need to access platform-specific APIs that are not intrinsically available from your shared code. For example, you might want to take a picture, perform file I/O, or play audio. The recommended approach is to code an abstraction layer that will let you invoke the platform-specific API from shared code. This module shows you three techniques for doing this: Factory pattern, Service Locator pattern, and Dependency Injection.

- Locate dependencies using the Factory Pattern
- Use a Service Locator to register and retrieve dependencies
- Use an IoC container to automatically inject dependencies

### Useful links

-	[Exploring the Factory Design Pattern](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee817667(v=pandp.10)) 
- [Dependency Injection](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/dependency-injection)
- [Introduction to DependencyService](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/dependency-service/introduction)

### Exploring on your own

-	[Dependency resolution in Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/internals/dependency-resolution#injecting-a-dependency-resolution-method) 

## Mobile application architecture (XAM301)

> **Recommended Prerequisites**:  Introduction to Cross-Platform Mobile Development (XAM110)

You're going to focus on how to properly architect your application to separate the presentation from the business logic and data that drives it. You'll look at three primary patterns which are popular in the mobile world: Model-View-Controller (MVC), Model-View-Presenter (MVP), and Model-View-ViewModel (MVVM).

- Apply Model-View-Controller to a Xamarin.iOS app
- Apply Model-View-Presenter to a Xamarin.Android app
- Apply Model-View-ViewModel to a Xamarin.Forms app

### Useful links

- [Architecture](https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/building-cross-platform-applications/architecture)
-	[The Model-View-ViewModel Pattern](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/mvvm) 
- [Summary MVVM](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/creating-mobile-apps-xamarin-forms/summaries/chapter18)

### Exploring on your own

-	[Enterprise Application Patterns using Xamarin.Forms eBook](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/enterprise-application-patterns/) 


## Diagnosing Memory Management Issues (XAM370)

There are two conceptual areas of memory in a Xamarin app: the managed memory in the Mono runtime and the memory space used for native objects. Standard .NET/Mono objects are allocated on the managed side while types like UI elements have a representation in both areas. This means there are several cases to consider when troubleshooting the memory usage of your app. This module begins by showing you how memory leaks happen in managed memory even with a sophisticated garbage collector and how to discover and fix them. It then shows you several memory issues that are specific to Xamarin.iOS and Xamarin.Android.

- Identify and fix memory leaks in your code
- Recognize and fix Xamarin.iOS specific memory problems
- Recognize and fix Xamarin.Android specific memory problems

### Useful links

-	[Garbage Collection](https://docs.microsoft.com/en-us/xamarin/android/internals/garbage-collection) 
- [Implementing a Dispose method](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/implementing-dispose)


### Exploring on your own

-	[Cross-Platform Performance](https://docs.microsoft.com/en-us/xamarin/cross-platform/deploy-test/memory-perf-best-practices) 
- [Xamarin Profiler](https://docs.microsoft.com/en-us/xamarin/tools/profiler/)
