# ASP.NET Core Build

BuildNinja configuration for an ASP.NET Core web application.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/abheekm/ASP_NET_Core_App |
| **Branch** | qa |
| **Stack** | ASP.NET Core |

## About This Project

A sample ASP.NET Core web application used for testing .NET builds in CI/CD pipelines. Demonstrates the simplest possible .NET build configuration with BuildNinja.

## What This Demonstrates

- .NET CLI build commands (`dotnet build`)
- Solution file compilation
- Simple single-step builds
- Cross-platform .NET builds

## Agent Requirements

- .NET SDK 6.0+ (recommended: .NET 8.0)

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `dotnet build ASP_NET_Core_App.sln` | Build the solution |

## Artifacts

- `bin/` - Compiled binaries
- `obj/` - Build intermediate files
