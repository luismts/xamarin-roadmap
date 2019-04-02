# Introduction to C#

This track provides an introduction to the C# programming language.

## Introduction to C# [CSC101]

A key step in becoming a C# developer is building and running your first program. Even a simple program requires that you have your development machine set up correctly and that you know the core C# syntax. In this module, you will install Visual Studio, create a console application, write code to perform a calculation, and display output to the user.

- Know the role of C# and Xamarin
- Set up and run your first program
- Learn the fundamentals of C#

### Useful links

- [C# Tour](https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/)
- [Eight Reasons C# is the Best Language for Mobile Development](https://blog.xamarin.com/eight-reasons-c-sharp-is-the-best-language-for-mobile-development/)
- [Is C# good for mobile development?](https://www.quora.com/Is-C-good-for-mobile-development)
-	[Get Visual Studio](https://visualstudio.microsoft.com/vs/) 
- [Quickstart: Use Visual Studio to create your first C# console app](https://docs.microsoft.com/en-us/visualstudio/ide/quickstart-csharp-console)

### Exploring on your own

- [C# Fundamentals](https://www.tutorialspoint.com/csharp/)
- [C# Guide](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [Introduction to C#](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/index)

## Branching and Looping [CSC102]

Programs often need to evaluate data and make choices based on the values they discover. This module covers how to read user input, branch or loop based on the input values, and convert the results to strings for display.

- Implement conditional branching
- Discover and use loops in your code

### Useful links

- [Learn conditional logic with branch and loop statements](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/branches-and-loops)

### Exploring on your own

- [Selection statements (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/selection-statements)
- [Iteration Statements (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/iteration-statements)

> Recommended Prerequisites: Introduction to C# [CSC101].

## Object-Oriented Programming [CSC103]

There are many ways to organize your code that all lead to correct programs. One of the challenges of being a developer is evaluating these different options and choosing the one that best fits your goals. One popular approach is called Object-Oriented Programming (OOP). This module introduces the core OOP principles and shows you how to apply them to your C# code.

- Determine classes and relationships in a program
- Create a class with fields to maintain state
- Use enumerations to define constant values

### Useful links

- [Object-Oriented Programming (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming)
- [Enum](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/enum)
- [Enumeration types (C# Programming Guide)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/enumeration-types)

<!-- ### Exploring on your own -->

> Recommended Prerequisites: Branching and Looping [CSC102]

## Adding Behavior into our Apps [CSC104]

A C# class is a container that groups together data and its associated operations. The data is typically stored in fields with a construct called a property controlling access. The operations are called methods and provide the logic to perform work related to the class. This module shows you how to define and invoke both properties and methods. By the end of the module, you will be able to write a class that models the data and behavior of a real-world object.

- Create a class with methods to provide behavior
- Utilize properties to hide our fields

### Useful links

- [Classes](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/classes)
- [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/methods)
- [Properties](https://docs.microsoft.com/en-us/dotnet/csharp/properties)

### Exploring on your own

- [Classes and Structs](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/)

> Recommended Prerequisites: Object-Oriented Programming [CSC103]

## Building a Console Application [CSC105]

Previous module introduced the core features of programming with C#. This module will put these individual pieces together by guiding you through the creation of a larger-scale application. You will build a Console Application that reads user input, converts the input from a string to a numeric type, performs a calculation that includes branching and looping, and display the results to the user.

- Define a custom type using a class
- Create properties to control access to data
- Repeat a block of code with a loop
- Create methods to add behavior to classes

### Useful links

- [Console Application](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/console-teleprompter)

### Exploring on your own

- [Tutorial: Create a simple C# console app in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-console?view=vs-2017)
- [Inside a C# program](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/)

> Recommended Prerequisites: Adding Behavior into our Apps [CSC104]

## Method Parameters and Constructors [CSC106]

A key part of working with methods is sending arguments in and getting results out. This module shows you how to use optional parameters to add flexibility to method inputs and how to use output parameters to return multiple values. Another important issue for any programming languages is initialization of data fields. Whenever you create a new object, you should think about what values you should assign to the fields to ensure the object is ready for use. This module covers how to use special methods called constructors to perform this initialization.

- Pass information into methods
- Receive information from methods
- Initialize objects using constructors

### Useful links

- [Passing Parameters](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/passing-parameters)
- [return](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/return)
- [Using Constructors](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/using-constructors)

### Exploring on your own

- [Constructors](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/constructors)

> Recommended Prerequisites: Building a Console Application [CSC105]

## Collections [CSC107]

Almost every program will have a collection of data. For example, an email app stores a list of your contacts, a web browser displays the websites you have visited, and a weather program shows the forecast for your favorite cities. To code this, you would create a collection by storing your values inside a data structure. This module shows you how to use three of the most popular collection types: array, List, and Dictionary.

- Use arrays to load static data sets
- Use lists and dictionaries to manage data

### Useful links

- [Collections](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)
- [Arrays](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/)

> Recommended Prerequisites: Method Parameters and Constructors [CSC106]

## Debugging and Exceptions [CSC108]

Even careful programmers make mistakes. They might forget to validate user input or let a loop continue to run for one extra iteration after it should have stopped. Issues like these are so common that finding and fixing errors is considered a core programming skill. This module shows you two debugging techniques: using a debugger to examine the state of your program during its execution and using exceptions to write code that responds to problems as the program runs.

- Use the debugger to examine executing code 
- Throw and catch exceptions to respond to errors

### Useful links

- [Tutorial: Learn to debug C# code using Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-debugger?view=vs-2017)
- [try-catch](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch)
- [throw](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/throw)

### Exploring on your own

- [Exception Handling Statements](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/exception-handling-statements)

> Recommended Prerequisites: Collections [CSC107]

## Inheritance and Polymorphism [CSC109]

Computer programming involves creating a software model of things that exist in the real world. One important real-world relationship is often described as "is-a". For example, a dog is-a animal, a truck is-a vehicle, and an undergraduate is-a student. C# includes a feature called inheritance that lets you model the is-a relationship in your code. This module shows you how to use inheritance to model the types in your world that are related though is-a. It also introduces a related idea called polymorphism that helps your code handle multiple different data types without the need to write a specific case for each one.

- Use inheritance to eliminate repeated code
- Use virtual methods and polymorphism to write generic code

### Useful links

- [Inheritance in C# and .NET](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/inheritance)
- [Polymorphism](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/polymorphism)

### Exploring on your own

- [virtual](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/virtual)

> Recommended Prerequisites: Debugging and Exceptions [CSC108]

## GC Fundamentals [CSC270]

Most modern programming languages and runtimes include Garbage Collection because it relieves the developer of some of the burden of managing memory. Unfortunately, it is not completely automatic because the way your write your code impacts the performance of the Garbage Collector. This module shows you how to help the Garbage Collector do its job efficiently. You will apply coding strategies that can reduce the workload of the Garbage Collector and use environment variables to tune the Garbage Collector's behavior for the way your app uses memory.

### Useful links

- [Fundamentals of garbage collection](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/fundamentals)

### Exploring on your own

- [GC Class](https://docs.microsoft.com/en-us/dotnet/api/system.gc?view=netframework-4.7.2)

> Recommended Prerequisites: Introduction to C# [CSC101]

## Managing Non-Memory Resources [CSC271]

Apps often need to work with resources such as local databases, files, and network connections. The usage pattern is similar in all cases: acquire the resource, use it, then release it when you are finished. Releasing the resource is tricky because you might accidentally omit the clean-up code or it might not be obvious when you are finished if the same resource is used from many parts of your program. This module shows you three ways to make release of non-memory resources less error prone: IDisposable, Finalizers, and SafeHandle.

### Useful links

- [What is "managed code"?](https://docs.microsoft.com/en-us/dotnet/standard/managed-code)
- [IDisposable Interface](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable?view=netframework-4.7.2)
- [Cleaning Up Unmanaged Resources](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/unmanaged)
- [Finalizers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/destructors)
- [Using safe handles](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/implementing-dispose#using-safe-handles)

### Exploring on your own

- [Cleaning Up Unmanaged Resources](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/unmanaged)
- [Memory Management and Garbage Collection in .NET](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/memory-management-and-gc)
- [SafeHandle Class](https://docs.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.safehandle?view=netframework-4.7.2)

> Recommended Prerequisites: GC Fundamentals [CSC270]

## Using Async and Await [CSC350]

Apps often need to perform long-running operations like downloading data from the cloud or accessing the local file system. The libraries that do this work for you generally offer asynchronous APIs that let your app stay responsive to user input while these operations run in the background. This module shows you how to use the async and await keywords to write this type of asynchronous code. You will also see the details of the underlying implementation and discuss some best practices to follow when utilizing this C# feature.

### Useful links

- [async](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/async)
- [await](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/await)

### Exploring on your own

- [Asynchronous programming](https://docs.microsoft.com/en-us/dotnet/csharp/async)
- [The Task asynchronous programming model in C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)

> Recommended Prerequisites: GC Fundamentals [CSC270]

## Writing Multithreaded Mobile Applications [CSC351]

If an application appears to be stuck, the user may assume it has crashed and restart or even uninstall the app. The core technique to keep your app responsive is to delegate work to background threads so the UI thread is available to monitor user actions. This module shows you how to use Tasks to move CPU-bound work onto background threads. You will see how to create and manage Tasks, how to handle exceptions, and how to support cancellation.

### Useful links

- [Task Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.tasks.task?view=netframework-4.7.2)
- [Exception handling (Task Parallel Library)](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/exception-handling-task-parallel-library)
- [How to: Cancel a Task and Its Children](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/how-to-cancel-a-task-and-its-children)

### Exploring on your own

- [Managed threading basics](https://docs.microsoft.com/en-us/dotnet/standard/threading/managed-threading-basics)
- [Device.BeginInvokeOnMainThread(Action) Method](https://docs.microsoft.com/en-us/dotnet/api/xamarin.forms.device.begininvokeonmainthread?view=xamarin-forms)
- [Xamarin.Essentials: MainThread](https://docs.microsoft.com/en-us/xamarin/essentials/main-thread)

> Recommended Prerequisites: Using Async and Await [CSC350]

## Introduction to Thread Safety and Synchronization [CSC352]

Multithreaded code can increase parallelism and therefore help your app run faster. However, multiple threads require you to manage their access to any shared data. Adding the right amount of synchronization is tricky because too little results in corrupted data while too much decreases parallelism and slows down your app. This module begins with a thorough discussion of what makes code unsafe so you will be able to identify the parts of your app that require synchronization. It then shows you how to use the Monitor class and the C# lock keyword to synchronize access to shared data.

### Useful links

- [Monitor Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.monitor?view=netframework-4.7.2)
- [lock statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/lock-statement)

### Exploring on your own

- [Managed threading best practices](https://docs.microsoft.com/en-us/dotnet/standard/threading/managed-threading-best-practices)

> Recommended Prerequisites: Writing Multithreaded Mobile Applications [CSC351]

## More about Synchronization [CSC353]

Managing multiple threads requires careful work in two areas: synchronizing access to shared data and coordinating the activity of threads working together on a common task. This module shows you two synchronization techniques: ReaderWriterLockSlim to allow multiple simultaneous reads and SemaphoreSlim to allow full access by a specific number of threads. The module also covers three coordination patterns: event-based with ManualResetEventSlim, countdown with CountdownEvent, and rendezvous with the Barrier class. Finally, the module surveys the thread-safe collections in the System.Collections.Concurrent namespace. 

### Useful links

- [ReaderWriterLockSlim Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.readerwriterlockslim?view=netframework-4.7.2)
- [SemaphoreSlim Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.semaphoreslim?view=netframework-4.7.2)
- [ManualResetEventSlim Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.manualreseteventslim?view=netframework-4.7.2)
- [CountdownEvent Class](https://docs.microsoft.com/en-us/dotnet/api/system.threading.countdownevent?view=netframework-4.7.2)

### Exploring on your own

- [Thread-Safe Collections](https://docs.microsoft.com/en-us/dotnet/standard/collections/thread-safe/)
- [System.Collections.Concurrent Namespace](https://docs.microsoft.com/en-us/dotnet/api/system.collections.concurrent?view=netframework-4.7.2)

> Note: This module is a continuation of CSC352.
