# API Navigator

Quick API endpoint navigation for multiple frameworks. Press Ctrl+Shift+A (Cmd+Shift+A on Mac) to search both files and API endpoints in your workspace, similar to IntelliJ IDEA's search everywhere feature.

🔌 [Install from VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=KindredZhang.api-navigator)

![Demo](docs/images/demo.gif)

## Features

- 🔍 Quick search for API endpoints using Ctrl+Shift+A (Cmd+Shift+A on Mac)
- 🎯 Direct navigation to endpoint definitions
- 📝 Support for context-path configuration
- 🔄 Real-time endpoint scanning
- 📊 Split view showing both files and API endpoints
- ⌨️ Customizable keyboard shortcuts

## Currently Supported

- Spring Boot (Java)
  - Request mappings (`@RequestMapping`, `@GetMapping`, etc.)
  - Context path from properties/yaml files
  - Nested path resolution

## Planned Support

- Express.js (Node.js)
- FastAPI (Python)
- Laravel (PHP)
- ASP.NET Core (C#)

## Usage

1. Press `Ctrl+Shift+A` (or `Cmd+Shift+A` on Mac)
2. Type part of your API path, class name, or method name
3. Select from the results to jump directly to the endpoint definition

## Requirements

- Visual Studio Code ^1.85.0
- Java projects (for current version)

## Known Issues

- Currently only supports Spring Boot REST APIs
- Work in progress for other frameworks

## Release Notes

### 0.0.3
- Added support for custom keyboard shortcuts
- Enhanced performance and bug fixes

### 0.0.1 / 0.0.2
Initial release:
- Basic Spring Boot REST API endpoint navigation
- Support for application.properties and application.yml
- Quick search functionality

## Contributing

This extension is in active development. Feel free to contribute or suggest new features!

I'm an individual developer looking to connect with others. Feel free to reach out at kindred.zhang.life@gmail.com - I'd love to hear your thoughts and ideas!

## License

MIT

---

**Enjoy!**

## Keyboard Shortcuts

Default shortcuts:
- Windows/Linux: `Ctrl+Shift+A`
- macOS: `Cmd+Shift+A`

To customize the keyboard shortcut:
1. Open Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Preferences: Open Keyboard Shortcuts"
3. Search for "API Navigator"
4. Click the pencil icon to edit the shortcut
5. Press your desired key combination
6. Press Enter to save

Or directly open keyboard shortcuts:
- Windows/Linux: `Ctrl+K Ctrl+S`
- macOS: `Cmd+K Cmd+S`