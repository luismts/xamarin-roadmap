# Azure {#Azure}

This track focuses on creating Azure-hosted services and accessing them from your Xamarin client apps. Topics include the Azure portal, Azure Mobile App Service, connecting to Azure from a mobile client, and authentication.

## Introduction to Azure (AZR101) {#introduction-azure}

> **Recommended Prerequisites**: Getting Started with Xamarin (XAM101)

Azure is Microsoft's subscription-model cloud-computing platform. It offers a wide variety of processing, storage, networking, and API services. This course gets you started with Azure by surveying several of the most popular services and presenting the Azure pricing model. It then shows you two core tasks: creating an Azure account and using the Azure web portal to provision a resource such as a virtual machine.

### Useful links {#useful-links-AZR101}

- []()
- []()

### Exploring on your own {#explorando-AZR101}

- []()
- []()

## Building an Azure Mobile App Service (AZR110) {#building-azure-mobile-app-service}

> **Recommended Prerequisites**: Introduction to Azure (AZR101)

Many business solutions have similar needs: a database to store information, server-side logic for processing client requests, and a REST-based API to allow client access to the data. Azure provides the building blocks to implement all these features grouped together under the term Azure Mobile App. This course shows you how to create a new Azure Mobile App and implement the server-side components to store and expose your data. You will use a SQL database for storage and see two techniques for creating the web service: Node.js and ASP.NET. 

Note: You will need an Azure account to complete this course. See AZR101 for details on creating an account. In addition, to take advantage of the ASP.NET-based labs, you will need to be on Windows, use Visual Studio, and install the Azure SDK.

### Useful links {#enlaces-utiles-AZR110}

- []()
- []()

### Exploring on your own {#useful-links-AZR110}

- []()
- []()

## Building an Azure Mobile App Client (AZR115) {#building-azure-mobile-app-client}

> **Recommended Prerequisites**: Introduction to Azure (AZR115)

Suppose you have your data stored in the Azure cloud and are coding Xamarin apps to show the data to clients on multiple platforms. You could use HttpClient to transfer JSON-encoded data and a serializer to convert between JSON and your model objects. This works but is tedious to implement. A better option is the Azure client SDK because it simplifies basic CRUD operations and offers advanced features such as offline caching. This course shows you how to use MobileServiceClient from the Azure SDK to work with your Azure data tables. You will consume data from an Azure service, add support for offline caching and synchronization, and manage data conflicts when they arise.

### Useful links {#enlaces-utiles-AZR115}

- []()
- []()

### Exploring on your own {#useful-links-AZR115}

- []()
- []()

## Authentication with Azure  (AZR110) {#authentication-azure}

> **Recommended Prerequisites**: Introduction to Azure (AZR120)

If you store customer or business data in Azure, you will need to secure it from unauthorized use. Azure offers many options for authenticating users and determining what data they can access. These security options are disabled by default which is convenient for testing or public APIs; however, you should enable them before moving your code into production. This course shows you how to configure both the server and client sides to secure your Azure data. On the server, you will enable user authentication with Azure Active Directory or a third-party provider (Google, Microsoft Account, Facebook, and Twitter). On the client, you will set up MobileServiceClient to use OAuth and then manage the access token so the user does not need to log in every time they run your app.

### Useful links {#enlaces-utiles-AZR120}

- []()
- []()

### Exploring on your own {#useful-links-AZR120}

- []()
- []()
