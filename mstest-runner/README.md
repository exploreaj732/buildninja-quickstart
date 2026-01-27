# MSTest Runner Build

BuildNinja configuration demonstrating the **MSBuild runner**.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/abheekm/MSTest_Runner_App |
| **Branch** | master |
| **Stack** | .NET with MSBuild |

## About This Project

A .NET application specifically designed to demonstrate BuildNinja's native MSBuild runner (`runner_msbuild`). This shows how to use MSBuild parameters directly rather than the `dotnet` CLI.

## What This Demonstrates

- **MSBuild runner** (`runner_msbuild`) - BuildNinja's native runner
- MSBuild parameters and targets
- NuGet package restoration via MSBuild
- Configuration-specific builds (Debug/Release)

## Agent Requirements

- .NET SDK 8.0
- MSBuild (included with Visual Studio or .NET SDK)
- **Windows agent recommended**

## Build Steps

| Step | Runner | Parameters |
|------|--------|------------|
| 1 | `runner_msbuild` | `/t:restore /p:Configuration=Debug /t:Rebuild` |

## MSBuild Parameters Explained

| Parameter | Description |
|-----------|-------------|
| `/t:restore` | Restore NuGet packages |
| `/p:Configuration=Debug` | Build in Debug mode |
| `/t:Rebuild` | Clean and rebuild the solution |

## Artifacts

- `bin/` - Compiled binaries
