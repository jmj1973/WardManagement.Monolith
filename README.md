# WardManagement.Monolith
 Use Visual Studio Code and .Net 6.0
 
 [Release](doc/RELEASE.md)

## Visual Studio Code
 Microsoft Visual Studio Code (64-bit) - Current
 Version 1.74.3

## .Net 6.0
 Microsoft .NET SDK 6.0.405

## Running the code
 Check the gode out
 Open in Visual Studio
 Change appsettings.json to your SQL/SQLExpress DB

 ## Steps

 1. Create a blank soloution
    - Folder structure: src and tests
    ```
    dotnet new sln -o WardManagement.Monolith
    cd WardManagement.Monolith
    mkdir doc
    mkdir src
    mkdir test
    ```  
    
 2. Setup the project
    ```
    dotnet new mvc -f net6.0 -au Individual -n WardManagement.Monolith -o src/WardManagement.Monolith
    dotnet sln add src/WardManagement.Monolith/WardManagement.Monolith.csproj
    ```

