# Apache Ant Build

BuildNinja configuration for a sample Ant-based Java project.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/piona/ant-sample |
| **Branch** | master |
| **Author** | [Piotr Nazimek](https://github.com/piona) (Poland) |
| **Forks** | 155+ |

## About This Project

A sample Java project demonstrating Apache Ant build automation. This is a popular learning resource with over 155 forks on GitHub, created as an example of Java project structure with a complete Ant build file.

## What This Demonstrates

- Apache Ant build targets (compile, clean, build, rebuild, run)
- Javadoc documentation generation
- JAR packaging
- Multi-step build workflows
- Artifact collection from multiple directories

## Agent Requirements

- Java JDK 8+
- Apache Ant

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `ant -p` | List available targets |
| 2 | `ant compile` | Compile source code |
| 3 | `ant clean` | Clean build directory |
| 4 | `ant build` | Build the project |
| 5 | `ant rebuild` | Clean and rebuild |
| 6 | `ant run` | Run the application |
| 7 | `ant doc` | Generate Javadoc |
| 8 | `ant jar` | Create JAR package |

## Artifacts

- `build/` - Compiled classes and build output
- `doc/` - Generated Javadoc documentation
