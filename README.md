# .NET Project Template

A clean architecture .NET project template with pre-configured layers and essential development tools for rapid project setup.

## Features

- Clean Architecture with Domain, Application, Infrastructure, and API layers
- Pre-configured project dependencies and references
- VSCode workspace settings and extensions recommendations
- xUnit testing project with proper structure

## Project Structure

```
├── ProjectTemplate.Domain/          # Entities, value objects, domain logic
├── ProjectTemplate.Application/     # Use cases, DTOs, application services
├── ProjectTemplate.Infrastructure/  # Data access, external services
├── ProjectTemplate.API/            # Controllers, API configuration
├── ProjectTemplate.Tests/          # Unit and integration tests
└── ProjectTemplate.sln             # Solution file
```

## Getting Started

1. **Use this template** to create a new repository
2. **Clone your repository** locally
3. **Rename the projects** - Replace `ProjectTemplate` with your project name in:
   - Project folder names
   - .csproj files
   - Namespace declarations
   - Solution file

4. **Build and run**:
   ```bash
   dotnet restore
   dotnet build
   dotnet watch run
   ```


## Development

The template includes VSCode settings for optimal .NET development experience with proper formatting, IntelliSense, and debugging configuration.

## Testing

```bash
dotnet test
```

## License

MIT License - feel free to use this template for any project.