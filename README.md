# Different Editing Modes in Blazor Tree Grids

A quick-start Blazor Web App with WebAssembly interactivity (.NET 10) that helps you edit hierarchical data in a Syncfusion Blazor Tree Grid. In this example, you'll learn how to enable editing in a Tree Grid and explains you the available editing modes. Then it explains how to add a command column in a Tree Grid.

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/getting-started

**Online example**: https://blazor.syncfusion.com/demos/tree-grid/inline-editing

## Prerequisites

* [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
* Visual Studio 2022 / Visual Studio Code

## Project structure (.NET 10)

```
TreeGridEditingSample/          # Server project (hosts the WASM client)
├── Components/
│   ├── App.razor
│   ├── Routes.razor
│   ├── _Imports.razor
│   ├── Layout/
│   └── Pages/
├── Properties/
├── wwwroot/
├── Program.cs
└── TreeGridEditingSample.csproj
TreeGridEditingSample.Client/    # WebAssembly client project (interactive components)
├── Pages/
│   └── Home.razor              # Tree Grid editing sample
├── wwwroot/
├── Program.cs
└── TreeGridEditingSample.Client.csproj
```

## How to run the project

* Checkout this project to a location in your disk.
* Restore the NuGet packages by rebuilding the solution.
* Run the project.

## Further help
For more help, check the [ASP.NET Core Blazor documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor/).