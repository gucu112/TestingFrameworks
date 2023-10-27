# Testing Frameworks

> This is simple repository which will contain various projects that show how you can approach building your own framework using some set of technologies and tools.

## Table of Contants* [Getting started](#getting-started)  * [Prerequisites](#prerequisites)  * [Building](#building)  * [Running](#running)* [Deployment](#deployment)* [Built with](#build-with)  * [PlaywrightXunit](#playwrightxunit)  * [PlaywrightXunitParallel](#playwrightxunitparallel)  * [PlaywrightSpecflowXunit](#playwrightspecflowxunit)* [Contributing](#contributing)* [Versioning](#versioning)* [Authors](#authors)* [License](#license)## Getting startedSimply open the solution file (`TestingFrameworks.sln`) from main project directory.### Prerequisites#### Playwright
```
pwsh bin/Debug/net6.0/playwright.ps1 install
```

If `pwsh` is not available, you have to [install PowerShell](https://docs.microsoft.com/powershell/scripting/install/installing-powershell).### BuildingUse Visual Studio to build the tests.### RunningUse Visual Studio Test Explorer tool to run the tests.## DeploymentThere are no deployment procedure established yet.## Build with### PlaywrightXunit* [Playwright](https://playwright.dev/dotnet/)* [Xunit](https://xunit.net/)* [Xunit.SkippableFact](https://github.com/AArnott/Xunit.SkippableFact)### PlaywrightXunitParallel### PlaywrightSpecflowXunit## ContributingThere are no contribution rules established yet.## Versioning

Project versioning pattern is defined as follows:

```
v{yy}.{M}.{d}.{r}
```

**Legend:**

- {yy} - 2-digits year, range from 00 to 99
- {M} - month, range from 1 to 12
- {d} - day of the month, range from 1 to 31
- {r} - revison number, incrementing for each daily version, starting from 0

## Authors

- **Bartlomiej Roszczypala** - [Gucu112](https://github.com/Gucu112)

See also the list of [contributors](https://github.com/gucu112/TestingFrameworks/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
