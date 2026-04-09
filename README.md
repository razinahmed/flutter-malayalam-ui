# Flutter Malayalam UI

![Flutter](https://img.shields.io/badge/Flutter-Widgets-02569B)
![Dart](https://img.shields.io/badge/Dart-Language-0175C2)
![License](https://img.shields.io/badge/License-MIT-green)

A Flutter widget library tailored for building Malayalam-language applications. Provides pre-styled components, Malayalam-optimized typography, and culturally appropriate design patterns for mobile and web apps.

## Features

- Ready-to-use Flutter widgets designed for Malayalam text rendering
- Typography presets optimized for Malayalam script readability
- Kerala-inspired color theme with CSS custom properties for web targets
- Dark mode support out of the box
- Compatible with Flutter mobile, web, and desktop platforms

## Tech Stack

| Technology | Purpose                     |
|------------|-----------------------------|
| Flutter    | UI framework                |
| Dart       | Programming language        |
| CSS3       | Web target theming          |
| Make       | Build automation            |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/flutter-malayalam-ui.git
cd flutter-malayalam-ui
```

2. Install dependencies:

```bash
flutter pub get
```

3. Import and use widgets in your app:

```dart
import 'package:flutter_malayalam_ui/widgets.dart';

MalayalamText(
  text: 'കേരളം',
  style: MalayalamTextStyle.headline,
)
```

## Theme Configuration

The web theme provides CSS variables for consistent styling:

```css
.theme {
  --primary: #00d4aa;
  --background: #1e1e2e;
}
```

## Build

```bash
make build
make test
```

## Project Structure

```
flutter-malayalam-ui/
  styles/
    theme.css       # Web theme variables
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. Please ensure widgets render Malayalam script correctly across different screen sizes.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
