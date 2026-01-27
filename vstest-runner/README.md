# VSTest Runner Build

BuildNinja configuration demonstrating the **VSTest runner**.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/abheekm/VSTest_Runner_App |
| **Branch** | master |
| **Stack** | .NET with VSTest |

## About This Project

A .NET application specifically designed to demonstrate BuildNinja's native VSTest runner (`runner_vstest`). This shows how to build a solution and then run Visual Studio tests.

## What This Demonstrates

- **VSTest runner** (`runner_vstest`) - BuildNinja's native runner
- .NET solution builds with `dotnet build`
- Test assembly execution
- Build + Test workflow

## Agent Requirements

- .NET SDK 8.0
- Visual Studio Test Platform (included with .NET SDK)
- **Windows agent recommended**

## Build Steps

| Step | Runner | Description |
|------|--------|-------------|
| 1 | `runner_cmd` | Build solution with `dotnet build` |
| 2 | `runner_vstest` | Execute tests from compiled assembly |

## VSTest Configuration

| Property | Value |
|----------|-------|
| Test Assembly | `bin\Debug\net8.0\VSTest_Runner_App.dll` |

## Artifacts

- `bin/` - Compiled binaries
- `TestResults/` - Test result files (TRX format)
