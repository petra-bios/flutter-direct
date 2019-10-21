# flutter_direct

Flutter Direct is a Design System for Home Credit Indonesia Tippers App.

## Usage

To use this plugin, add flutter_direct as a [dependency in your pubspec.yaml file](https://flutter.dev/docs/development/packages-and-plugins/using-packages).

### Example


Please see the example app of this plugin for a full example.

```dart
  DirectText(
    data: 'Font Family - Pt Sans',
    fontFamily: DirectFont.PtSans,
    color: Colors.white,
  ), 
  

 DirectFilledButton(
    text: "Active Button",
    fontSize: 16,
    buttonState: DirectButtonState.Active,
    fontFamily: DirectFontFamily.PtSans,
    fontWeight: FontWeight.normal,
    onTap: () {},
    ),
```