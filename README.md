![Workflow Status](https://github.com/kogelnikp/blazor-rock-paper-scissors/workflows/gh-pages/badge.svg)

# Rock, Paper, Scissors! with Blazor WebAssembly 

This is a demo application which shows how to create a simple Rock, Paper, Scissors! game using Blazor WebAssembly. All game logic is run in the browser, which means there is no server side code involved. This repo also contains a GitHub action which automatically deploys the app to GitHub pages.

## Demo

https://rockpaperscissors.kogelnikp.eu/

## Installation

These tools are required to run the app:
* .NET Core 3.1 SDK (>= 3.1.300)
* Browser supported by Blazor WebAssembly (find supported browsers [here](https://docs.microsoft.com/en-us/aspnet/core/blazor/supported-platforms?view=aspnetcore-3.1#blazor-webassembly))

Restore all required NuGet packages with

```sh
dotnet restore
```

## Usage

1. Run the app either in Visual Studio (Code) or using the command line with

```sh
cd src
dotnet run
```

2. Open the app in your browser on http://localhost:5000/ when using the dotnet CLI or on http:/localhost:62000/ when using IIS Express

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Acknowledgements

* Basic rock, paper, scissors image taken from [FreeSVG](https://freesvg.org/rock-paper-scissors)