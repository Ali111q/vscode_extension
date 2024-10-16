# sai-flutter-snippet

**sai-flutter-snippet** is a Visual Studio Code extension designed to provide a set of useful Flutter and Dart code snippets to help you quickly scaffold commonly used Flutter widgets, classes, and structures. It aims to make your Flutter development faster and more efficient by reducing boilerplate code.

## Features

This extension includes several useful snippets for Flutter development, which can be triggered using a short prefix. Each snippet is carefully designed to streamline the process of writing Flutter apps.

### Available Snippets

1. **Flutter StatelessWidget**

   - Prefix: `flutterstateless`
   - Description: Creates a basic Flutter `StatelessWidget` with a pre-defined `build` method.
   - Output:

     ```dart
     import 'package:flutter/material.dart';

     class WidgetName extends StatelessWidget {
       const WidgetName({Key? key}) : super(key: key);

       @override
       Widget build(BuildContext context) {
         return Container();
       }
     }
     ```

2. **Flutter StatefulWidget**

   - Prefix: `flutterstateful`
   - Description: Creates a Flutter `StatefulWidget` with a separate `State` class.
   - Output:

     ```dart
     import 'package:flutter/material.dart';

     class WidgetName extends StatefulWidget {
       const WidgetName({Key? key}) : super(key: key);

       @override
       _WidgetNameState createState() => _WidgetNameState();
     }

     class _WidgetNameState extends State<WidgetName> {
       @override
       Widget build(BuildContext context) {
         return Container();
       }
     }
     ```

3. **Dart Class**

   - Prefix: `dartclass`
   - Description: Generates a Dart class with placeholders for the class name, methods, and fields.
   - Output:

     ```dart
     class ClassName {
       ClassName();

       void method() {
       }
     }
     ```

## Requirements

- **Dart SDK** and **Flutter SDK** should be installed and configured in Visual Studio Code. If you haven’t already set up Flutter, please refer to the [Flutter installation guide](https://flutter.dev/docs/get-started/install).
- Visual Studio Code with the Flutter and Dart extensions installed.

## How to Use

1. Install the extension from the VS Code marketplace (or via `.vsix` file).
2. Open any Dart or Flutter project.
3. Type the corresponding snippet prefix (e.g., `flutterstateless`) and press `Tab` or `Enter`.
4. The code snippet will be inserted, and you can quickly modify the placeholders by navigating through them with `Tab`.

## Extension Settings

No additional settings are required for this extension.

## Known Issues

Currently, there are no known issues. If you find any bugs or have suggestions for improving the snippets, feel free to report them.

## Release Notes

### 1.0.0

- Initial release with the following Flutter and Dart snippets:
  - `StatelessWidget`
  - `StatefulWidget`
  - Dart class

## Contributing

If you would like to contribute or suggest improvements, feel free to open a pull request or raise an issue in the repository. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Happy Fluttering!**
