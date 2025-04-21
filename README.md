# Get CLI Project

A Flutter project that utilizes the GetX framework for state management, routing, and dependency injection.

## Project Overview

This Flutter application is built with:
- Flutter SDK: >=3.1.2
- GetX (get: 4.6.6) for state management
- Supports multiple platforms: Android, iOS, Web, Windows, Linux, and macOS

## Features

- Material Design UI
- Cross-platform support
- GetX integration for:
  - State Management
  - Route Management
  - Dependency Injection

## Getting Started

### Prerequisites

- Flutter SDK (>=3.1.2)
- Dart SDK (compatible with Flutter SDK version)
- An IDE (Android Studio, VS Code, etc.)

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Navigate to the project directory and install dependencies:
```bash
flutter pub get
```

3. Run the application:
```bash
flutter run
```

### Project Structure

The project follows a standard Flutter application structure with GetX integration:

```
get_cli_project/
├── lib/               # Source code
├── test/             # Test files
├── android/          # Android-specific files
├── ios/              # iOS-specific files
├── web/              # Web-specific files
├── windows/          # Windows-specific files
├── linux/            # Linux-specific files
├── macos/            # macOS-specific files
└── pubspec.yaml      # Project dependencies
```

## Dependencies

Main dependencies include:
- `flutter`: The Flutter SDK
- `get: 4.6.6`: GetX framework for state management
- `cupertino_icons: ^1.0.2`: iOS-style icons

Development dependencies:
- `flutter_test`: For widget testing
- `flutter_lints: ^2.0.0`: Recommended lints for Flutter apps

## Development

This project follows Flutter's best practices and conventions. Make sure to:
- Run tests before submitting PRs
- Follow the lint rules defined in `analysis_options.yaml`
- Keep dependencies updated

## Building for Production

To build for production, use:

```bash
flutter build <platform>
```

Replace `<platform>` with:
- `apk` for Android
- `ios` for iOS
- `web` for web
- `windows` for Windows
- `linux` for Linux
- `macos` for macOS

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under standard terms - see the LICENSE file for details.

## Support

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

For GetX-specific questions, refer to the [GetX documentation](https://github.com/jonataslaw/getx).
