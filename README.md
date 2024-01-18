# Autodesk Inventor API
## Overview
This repository contains a simple C# application that I developed to interact with the Autodesk Inventor API. The primary goal of the code is to hide selected components within an Assembly document in Autodesk Inventor.

## My Steps to Complete the Application
1. Understanding the Copyright Notice
The code begins with a copyright notice from Autodesk, Inc. This indicates the terms under which the code is provided and the permissions granted for its use, modification, and distribution.

2. Initializing the Inventor Application Object
I started by initializing the Inventor.Application object. The code attempts to connect to an existing instance of Inventor. If that fails, it creates a new instance and sets it to be visible. The _started variable is used to determine whether the Inventor application should be shut down when the form is closed.

3. Designing the Windows Form
I designed a simple Windows Form (Form) using Visual Studio 2017. This form includes a button, "Hide Selected Components," which triggers the functionality to hide selected components in the active Assembly document.

4. Implementing the Button Click Event
The button1_Click event is triggered when the "Hide Selected Components" button is clicked. The code checks whether there is an open Assembly document, if it's the active document, and if there are selected components. If conditions are met, it hides the selected components in the Assembly document.

5. Handling Exceptions
Exception handling is implemented to catch any errors that may occur during the process. This includes checking whether the selected item is a component and displaying relevant messages.

6. Building and Running the Application
I built the solution in Visual Studio to generate the executable. Running the application, I tested it by opening an Assembly document in Autodesk Inventor and clicking the "Hide Selected Components" button.

## Screenshots 
### Before
![Screenshot (188)](https://github.com/mvanadana/InventorAPI/assets/149364066/7e881d41-3fbb-4ff6-b504-d9dc10bbe204)

### After

![Screenshot (189)](https://github.com/mvanadana/InventorAPI/assets/149364066/d27eebea-0b2c-4fda-84a7-13fea63b9802)
