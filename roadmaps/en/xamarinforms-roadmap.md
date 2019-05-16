# Xamarin.Forms {#xamarinforms}

Xamarin.Forms is perfect for cross-platform applications that display "forms over data" where the primary goal of the application is to display data in a standardized way. This track focuses on building Xamarin.Forms applications that target iOS, Android and Windows.

## Introduction to Xamarin.Forms (XAM120) {#introduction-xamarinforms}

> **Recommended Prerequisites**:  Introduction to Cross-Platform Mobile Development (XAM110) 

Xamarin.Forms lets you define a single UI that you share across all your supported platforms. This maximizes your ability to share code: you can share your UI and your business logic. In this course, you will create a new Xamarin.Forms application and define your shared UI in code. You will also see how to access platform-specific features such as the phone dialer or camera that do not have a shared-programming model integrated into Xamarin.Forms.

- Learn the basic structure of a Xamarin.Forms mobile app
- Define a shared UI for Android and iOS
- Deploy an app from Visual Studio to Android and/or iOS

### Useful links

-	[Build your first Xamarin.Forms App](https://docs.microsoft.com/en-us/xamarin/get-started/first-app/index) 
- [Create a Single Page Xamarin.Forms Application](https://docs.microsoft.com/en-us/xamarin/get-started/quickstarts/single-page)

### Exploring on your own

- [Xamarin.Forms Application Fundamentals](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/)
- [Xamarin.Forms User Interface Views](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/index)


##  XAML in Xamarin.Forms (XAM130) {#xaml-xamarinforms}

> **Recommended Prerequisites**:   Introduction to Xamarin.Forms (XAM120)

Xamarin.Forms lets you define your UI using the eXtensible Application Markup Language (XAML). This gives you a clean separation of UI and behavior and makes it easy to utilize a design expert and design tools. This course shows you how to define your UI in XAML. You will create pages and add controls, all in markup. You will also see how to access UI elements from code so you can subscribe to UI events and update UI properties as your data changes.

- Create the UI, and add controls for a Xamarin.Forms app using XAML
- Access XAML-based UI elements from code
- Subscribe to XAML-based UI events

### Useful links

- [eXtensible Application Markup Language (XAML)](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/index)
- [Xamarin.Forms XAML Basics](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-basics/)

### Exploring on your own

- [XAML Previewer for Xamarin.Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-previewer/)
- [XAML Markup Extensions](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/markup-extensions/)

##  Layout in Xamarin.Forms (XAM135) {#layout-xamarinforms}

> **Recommended Prerequisites**:   XAML in Xamarin.Forms (XAM130)

Xamarin.Forms apps run on a wide range of devices with varying screen sizes and pixel densities. It is challenging to create a UI that looks good and behaves correctly in all cases. Xamarin.Forms helps solve this problem by providing flexible layout containers that can calculate the size and position of your UI controls automatically; they even recalculate if the user rotates the device or changes the size of the app's window. This course contains in-depth coverage of StackLayout and Grid, the two most popular layout containers in Xamarin.Forms. It also shows you how to add scrolling when your UI is too large for the available screen area.

- Display views in a vertical or horizontal list using StackLayout
- Display views in rows and columns using Grid

### Useful links

- [XAML Controls](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-controls)
- [Xamarin.Forms Layouts](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/controls/layouts)

### Exploring on your own

- [StackLayout Class](https://docs.microsoft.com/en-us/dotnet/api/xamarin.forms.stacklayout?view=xamarin-forms)
- [Grid Class](https://docs.microsoft.com/en-us/dotnet/api/xamarin.forms.grid?view=xamarin-forms)

##  Resources and Styles in Xamarin.Forms (XAM140) {#resources-styles-xamarinforms}

> **Recommended Prerequisites**:   XAML in Xamarin.Forms (XAM130)

Using the same fonts and colors across your entire UI creates a consistent look-and-feel. Xamarin.Forms provides a way to define these values in one place and look them up everywhere they are used; this guarantees consistency across your app and makes updates simple. This course shows you how to define and apply a Resource both in code and in XAML. It also shows you how to group multiple settings into a Style so you can apply them all at once.

- Create consistent UI using Resources and Styles
- Apply the user's accessibility choices with built-in Styles

### Useful links

- [Styling Xamarin.Forms Apps using XAML Styles](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/styles/xaml/index)
- [Styling Xamarin.Forms apps using Cascading Style Sheets (CSS)](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/styles/css/index)

### Exploring on your own

- [Styling Xamarin.Forms Apps](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/styles/)

##  Navigation Patterns in Xamarin.Forms (XAM205) {#navigation-patterns-xamarinforms}

> **Recommended Prerequisites**:  Layout in Xamarin.Forms (XAM135)

Part of planning your app’s architecture is deciding how the user will move between Pages. Will users need to more forward/backward through a sequence of pages? Does your app have one start page or are there several top-level pages that are all important? Your choice of navigation should work well with your app’s content and feel native to each platform you target. This course shows you how to code two common navigation patterns: stack and tab. It includes guidelines to help you decide which pattern is appropriate for your app. The course also covers how the navigation infrastructure automatically adapts to the runtime platform and shows you how to customize the behavior when needed.

- Choose between stack and tab navigation for your app
- Implement stack and tab navigation
- Display transitory content using modal pages

### Useful links

- [Hierarchical Navigation](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/navigation/hierarchical)
- [Xamarin.Forms Tabbed Page](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/navigation/tabbed-page)
- [Xamarin.Forms Modal Pages](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/navigation/modal)

### Exploring on your own

- [Xamarin.Forms Navigation](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/navigation/)

##  Data Binding in Xamarin.Forms (XAM270) {#data-binding-xamarinforms}

> **Recommended Prerequisites**:   XAML in Xamarin.Forms (XAM130)

Most apps need to load data from code-behind into their UI and transfer user-entered data to their code-behind models. Data Binding offers a clean way to perform both tasks. Data Binding uses binding objects that tie two properties together and keep their values in sync as either changes. This course shows you how to create bindings both in code and in XAML. You will also see how to implement value converters for use when the types of the two properties are different.

- Synchronize data between your UI and code-behind using bindings
- Minimize coupling between your UI and code-behind to enable easy UI changes

### Useful links

- [Data Binding Basics](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-basics/data-binding-basics)

##  Using ListView in Xamarin.Forms (XAM280) {#listview-xamarinforms}

> **Recommended Prerequisites**:   Data Binding in Xamarin.Forms (XAM270)

Most apps need to present data collections in their UI. In this course, you will add a Xamarin.Forms ListView to your app, populate it with a collection of data objects, and handle item selection. You will also use the built-in cell templates to lightly customize the appearance of each row. Finally, you will implement two common user-experience patterns: pull-to-refresh and context actions.

ListView has a limited selection of built-in cell styles. These standard cells handle common cases and you should use them if they meet your needs. If not, you can create a custom cell that will uniquely represent your data and match the overall look-and-feel of your app. This course shows you how to define a row template, how to add headers/footers, and how to display grouped data. You will also survey several performance-tuning strategies including cell caching. 

- Create a ListView and populate it with items
- Respond when the user interacts with the ListView
- Customize the appearance of a ListView row by using built-in Cell types
- Create custom cell layouts for a ListView
- Use multiple cell layouts in a single ListView
- Group cells into sections

### Useful links

- [Xamarin.Forms ListView](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/)
- [ListView Data Sources](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/data-and-databinding)
- [Customizing ListView Cell Appearance](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/customizing-cell-appearance)
- [Customizing ListView Appearance](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/customizing-list-appearance)
- [ListView Interactivity](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/interactivity)

### Exploring on your own

- [ListView Performance](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/performance)

##  Master-detail and Drawer Navigation (XAM290) {#master-detail-and-drawer-navigation}

> **Recommended Prerequisites**:  Data Binding in Xamarin.Forms (XAM270), Using ListView in Xamarin.Forms (XAM280), Navigation Patterns in Xamarin.Forms (XAM205)

Building a great application means creating clear navigation path through your content. As your application grows in complexity, you need to provide a UI structure that allows users to quickly switch between multiple screens. In this course, you’ll explore two UI techniques using a master-detail relationship. You’ll learn how to switch between several pages of content using drawer navigation, and you’ll create a true master-detail UI that enables users to browse a large collection of data while taking advantage of available screen space. This course includes an in-depth look at the Xamarin.Forms MasterDetailPage and shows you best practices on co-ordinating between Master and Detail pages.

- Choose between split and pop-over for your master view
- Switch between pages using pop-over drawer navigation
- Display a collection using master-detail split view

### Useful links

- [Xamarin.Forms Master-Detail Page](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/navigation/master-detail-page)

### Exploring on your own

- [MasterDetailPage Class](https://docs.microsoft.com/en-us/dotnet/api/xamarin.forms.masterdetailpage?view=xamarin-forms#applies-to)

##  Design an MVVM ViewModel in Xamarin.Forms (XAM320) {#mvvm-xamarinforms}

> **Recommended Prerequisites**:   Data Binding in Xamarin.Forms (XAM270), Using ListView in Xamarin.Forms (XAM280), XAML in Xamarin.Forms (XAM130), Mobile Application Architecture (XAM301) 

We're going to focus on how to properly architect your application to separate the _presentation_ from the business logic and data that drives it. We'll be looking at three primary patterns which are popular in the mobile world: Model-View-Controller (MVC), Model-View-Presenter (MVP), and Model-View-ViewModel(MVVM).

- Identify when to use the Model-View-ViewModel pattern
- Use a viewmodel to drive visual behavior
- Improve code testability through data-bindable properties

### Useful links

- [Xamarin.Forms MVVM](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-basics/data-bindings-to-mvvm)

##  Xamarin.Forms Effects (XAM330) {#effects-xamarinforms}

> **Recommended Prerequisites**:  Data Binding in Xamarin.Forms (XAM270)

Xamarin.Forms UI elements are model objects that are converted to native platform controls at runtime. To take full advantage of each platform’s unique style and patterns you can work directly with the native controls rather than the Xamarin.Forms elements. This course shows you how to use Effects to access and customize the native peer controls. This gives you the same power to modify the appearance of your UI as a native developer.

- Apply an effect in Xamarin.Forms
- Create an effect to customize behavior
- Add configuration options to an effect

### Useful links

- [Introduction to Effects](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/effects/)
- [Creating an Effect](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/effects/creating)

### Exploring on your own

- [Xamarin.Forms Effects](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/effects/)

##  Xamarin.Forms Renderers (XAM335) {#renderers-xamarinforms}

> **Recommended Prerequisites**:  Xamarin.Forms Effects (XAM330)

What if your Xamarin.Forms app needs to display an interactive graph, a drawing surface, or a color picker? Xamarin.Forms lets you extend the set of existing UI elements by writing your own custom control to handle these cases. In this course, you will see how to use a Renderer to implement the UI and behavior for a fully custom control. In addition, you will use a Renderer to modify the behavior of an existing control to meet your app’s specific needs.

- Modify an existing control's renderer
- Create a new control with a new renderer
- Send notifications between a Xamarin.Forms element and native controls

### Useful links

- [Introduction to custom renderers](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/custom-renderer/introduction)
- [Renderer base classes and native controls](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/custom-renderer/renderers)

### Exploring on your own

- [Xamarin.Forms Custom Renderers](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/custom-renderer/)


