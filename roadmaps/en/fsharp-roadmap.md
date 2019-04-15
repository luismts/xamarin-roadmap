# Introduction to F#

This track provides an introduction to the F# programming language. This set of modules provides experienced C# developers with the knowledge they need to start programming in F#.

## Introduction to F# [FSC101]

Functional languages use the principle of data immutability to avoid variables that maintain state. This characteristic makes functional programs easier to validate and easier to execute in multithreaded or parallel-processing environments. This module introduces you to the F# functional programming language. You will see how to code a simple F# program and execute it using a command-line interpreter called the Read-Evaluate-Print-Loop (REPL). 

### Useful links

- [What is F#](https://docs.microsoft.com/en-us/dotnet/fsharp/what-is-fsharp)
- [F# Tour](https://docs.microsoft.com/en-us/dotnet/fsharp/tour)
- [Get started with F# and Xamarin](https://docs.microsoft.com/xamarin/cross-platform/platform/fsharp/)
-	[Get Visual Studio](https://visualstudio.microsoft.com/vs/) 
- [Introduction to Programming with F#](https://www.youtube.com/watch?v=Teak30_pXHk&list=PLEoMzSkcN8oNiJ67Hd7oRGgD1d4YBxYGC)

### Exploring on your own

- [F# Guide](https://docs.microsoft.com/en-us/dotnet/fsharp/)
- [Introduction to Functional Programming in F#](https://docs.microsoft.com/en-us/dotnet/fsharp/introduction-to-functional-programming/)
- [Learn F# through videos](https://docs.microsoft.com/en-us/dotnet/fsharp/#learn-f-through-videos)
- [The F# Software Foundation](https://fsharp.org/)

##  Projects in F# [FSC102]

To build a real-world F# application you will use a development environment to create a project and organize your source code into multiple files. You will want to integrate 3rd-party libraries and code your own custom types. This module takes you through the entire process of using Visual Studio to create and run an F# console application.

### Useful links

- [Get started with F# in Visual Studio](https://docs.microsoft.com/en-us/dotnet/fsharp/get-started/get-started-visual-studio)
- [Get started with F# in Visual Studio for Mac](https://docs.microsoft.com/en-us/dotnet/fsharp/get-started/get-started-with-visual-studio-for-mac)
- [Get Started with F# in Visual Studio Code](https://docs.microsoft.com/en-us/dotnet/fsharp/get-started/get-started-vscode)

### Exploring on your own

- [F# style guide](https://docs.microsoft.com/en-us/dotnet/fsharp/style-guide/)

> Recommended Prerequisites: Introduction to F# [FSC101].

## Data Structures in F# [FSC103]

Managing in-memory data is required in most apps and F# contains powerful data-storage and processing APIs to help you. The APIs are optimized for specific use-cases; for example, some work best if your data is static while others are intended for large data sets. This module shows you several common F# data structures and discusses the pros and cons of each. By the end of the module, you will be able to choose the right storage option for your application.

### Useful links

- [Choosing between collection functions](https://fsharpforfunandprofit.com/posts/list-module-functions/)

### Exploring on your own

- [F# Collection Types](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/fsharp-collection-types)
- [Which Types to Use](https://docs.microsoft.com/en-us/dotnet/fsharp/tour#which-types-to-use)

> Recommended Prerequisites: Projects in F# [FSC102].

## Using Async [FSC104]

Apps often need to perform long-running operations like downloading data from the cloud or accessing the local file system. The libraries that do this work for you generally offer asynchronous APIs that let your app stay responsive to user input while these operations run in the background. This module shows you how to use the async keyword to write this type of asynchronous code. You will also see the details of the underlying implementation and discuss some best practices to follow when utilizing this C# feature.

### Useful links

- [Async Programming in F#](https://docs.microsoft.com/en-us/dotnet/fsharp/tutorials/asynchronous-and-concurrent-programming/async)
- [Asynchronous Workflows](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/asynchronous-workflows)

### Exploring on your own

- [Asynchronous Workflows](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/asynchronous-workflows)
- [Important Info and Advice](https://docs.microsoft.com/en-us/dotnet/fsharp/tutorials/asynchronous-and-concurrent-programming/async#important-info-and-advice)


> Recommended Prerequisites: Data Structures in F# [FSC103]

##  Partial Application and Pattern Matching [FSC105]

One strength of functional languages is their ability to combine functions in concise yet powerful ways. For example, you can pass a function as a parameter to another function or adapt a general function to your specific needs by hardcoding some of the parameter values. This module shows you how to use currying and partial function application to create new functions that perform the exact operation you need. Another useful feature in many functional languages is pattern matching that lets you examine data values and branch based on some matching characteristic of the data. In this module, you will use pattern matching to select data from a collection and apply a function to transform it.

### Useful links

- [Pattern Matching](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/pattern-matching)


### Exploring on your own

- [Match expressions](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/match-expressions)

> Recommended Prerequisites: Data Structures in F# [FSC103].

##  Type Providers in F# [FSC106]

F# makes it easy to load external data into your app. An F# Type Provider encapsulates all the necessary operations: it connects to the data source, determines the shape of the data, constructs objects, and populates the objects with the external data. This module shows you how to use Type Providers in your application. You will see how to instantiate a provider, read data, and execute queries against the provider to select only the data you need.

### Useful links

- [Type Providers](https://docs.microsoft.com/en-us/dotnet/fsharp/tutorials/type-providers/)
- [Tutorial: Create a Type Provider](https://docs.microsoft.com/en-us/dotnet/fsharp/tutorials/type-providers/creating-a-type-provider)

### Exploring on your own

- [The F# Type Provider SDK](https://github.com/fsprojects/FSharp.TypeProviders.SDK)

> Recommended Prerequisites: Type Providers in F# [FSC105].
