# Prototype2

A Unity game development project built with C#.

## Project Overview

Prototype2 is a C# game project developed in Unity, featuring a modular architecture with separate assemblies for core gameplay and editor tools.

## Project Structure

```
Prototype2/
├── Assembly-CSharp/          # Main game runtime assembly
├── Assembly-CSharp-Editor/   # Editor tools and utilities
├── Prototype2.sln            # Visual Studio solution file
└── .gitignore                # Git configuration (excludes Unity artifacts)
```

## Prerequisites

- **Unity** - Latest LTS version recommended
- **.NET Framework** - Compatible with your Unity version
- **Visual Studio** or **Visual Studio Code** - For C# development
- **Git** - For version control

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Prototype2
   ```

2. **Open in Unity:**
   - Open Unity Hub
   - Click "Add" and select the project directory
   - Open the project with your preferred Unity version

3. **Open in Visual Studio:**
   - Open `Prototype2.sln` in Visual Studio
   - The solution will load both the runtime and editor assemblies

## Building

### In Unity
- Use the Build menu to generate platform-specific builds
- Ensure all scenes are properly configured in Build Settings

### Using Visual Studio
1. Open `Prototype2.sln`
2. Select Debug or Release configuration
3. Build the solution (Ctrl+Shift+B)

## Project Configuration

The project uses Visual Studio's Managed Game workload, which includes all necessary tools for game development with .NET and C#.

## Development Guidelines

- **Assembly-CSharp:** Contains core gameplay logic and runtime scripts
- **Assembly-CSharp-Editor:** Contains editor-specific tools, custom inspectors, and development utilities

## .gitignore

The project includes a configured .gitignore that excludes:
- Library folders (compiled assemblies)
- Temp folders (temporary build files)
- Build/Builds directories (compiled game builds)
- Logs directory (runtime logs)
- UserSettings directory (local user configurations)

This keeps the repository clean and focused on source files only.

## Contributing

1. Create a feature branch (`git checkout -b feature/YourFeature`)
2. Commit your changes (`git commit -m 'Add YourFeature'`)
3. Push to the branch (`git push origin feature/YourFeature`)
4. Open a Pull Request

## License

[Add your license information here]

## Contact

[Add contact information or author details here]

---

**Note:** Make sure to use the same Unity version across all team members to avoid compatibility issues with project files and assemblies.
