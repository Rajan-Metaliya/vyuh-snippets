# vyuh-snippets README

This is the README for your extension "vyuh-snippets". This extension provides code snippets for the [Vyuh framework](https://vyuh.tech/), making it easier to write and maintain your code.

## Features

- Provides a collection of useful code snippets for the [Vyuh framework](https://vyuh.tech/).
- Snippets are available for the Dart programming language.

## All Snippets list

- `vyuhSection` : Vyuh Section
- `vyuhApiBuilder` : Vyuh Api builder
- `vyuhFeature` : Feature Descriptor
- `vyuhPlugin` : Plugin Setup
- `vyuhContentItem` : Content Item Definition
- `vyuhLayoutConfig` : Layout Configuration
- `vyuhActionConfig` : Vyuh Action Config
- `vyuhDI` :Vyuh DI Register


### Example Snippet

Here is an example of a snippet provided by this extension:

```dart
final class $1ApiConfig extends ApiConfiguration<$2> {
  static const schemaName = 'feature.$1.configsSection';

  static final typeDescriptor = TypeDescriptor(
    schemaType: schemaName,
    title: 'Feature API Configuration ($1)',
    fromJson: $1ApiConfig.fromJson,
  );

  $1ApiConfig() : super(schemaType: schemaName);

  factory $1ApiConfig.fromJson(Map<String, dynamic> json) =>
      _$$1ApiConfigFromJson(json);

  @override
  Widget build(BuildContext context, $2? data) {
    return const Text('$1 API Config');
  }

  @override
  Future<$2?> invoke(BuildContext context) async {
    return null;
    // Invoke the API 
  }
}
```