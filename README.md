# Example of Displaying a Custom Background Instead of a Fill Color for Shapes in the Syncfusion Blazor Maps Component

## Overview

This sample demonstrates how to apply a custom SVG pattern as the background for map shapes using the Syncfusion [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-map) component. Instead of using a standard solid fill color, the implementation defines an SVG pattern directly within the Razor page and applies it to map shapes through the Maps layer configuration. This approach enables advanced visual customization and helps developers create distinctive geographic visualizations using custom textures and patterned fills.

## Key Features

- Demonstrates rendering a custom SVG pattern for map shapes.
- Uses an SVG `pattern` element defined within the Razor page.
- Applies the SVG pattern through the `Fill` property of `MapsShapeSettings`.
- Configures a `MapsLayer` to render geographic shape data with customized appearance.
- Demonstrates replacing traditional solid-color fills with reusable SVG-based textures.
- Shows how custom styling can enhance geographic visualization scenarios.
- Uses shape rendering within the Syncfusion Maps component to display patterned regions.
- Demonstrates styling customization without modifying the underlying shape data.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `Sample.sln`

3. Restore NuGet packages.
4. Ensure the startup project
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory containing `Sample.csproj`.

```bash
dotnet restore
dotnet run
```
## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://help.syncfusion.com/chart-sdk/blazor/maps/customization

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
