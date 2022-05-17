# Deckweiss lint rules

This package provides the Dart and Flutter lint rules used by [Deckweiss]🧡

It is highly influenced by [very_good_analysis] with a few small customizations.
## Usage

To use this package simply add `deckweiss_lints` to the `dev_dependencies` of your projects's `pubspec.yaml` file:

```yaml
dev_dependencies:
  deckweiss_lints: ^1.0.0
```

This could also be done by calling:

```sh
flutter pub add deckweiss_lints --dev
```

Then simply include it in your `analysis_options.yaml` file. 

```yaml
# If you want to use the latest available deckweiss_lints ruleset
include: package:deckweiss_lints/deckweiss_lints.yaml

# If you want to use a specific version of the deckweiss_lints ruleset
include: package:deckweiss_lints/deckweiss_lints.1.0.0.yaml
```

### Excluded files
- `/**.g.dart`
- `/**.freezed.dart`

[Deckweiss]: https://deckweiss.at
[very_good_analysis]: https://pub.dev/packages/very_good_analysis