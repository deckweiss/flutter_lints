# Deckweiss lint rules

This package contains all lint rules used by Deckweiss. It is considered 
an expansion of the [lints] and [flutter_lints] packages.

There are two sets of lints available:

* **lints**: Lints for dart applications. 

* **flutter**: Lints for flutter applications.

## Usage

Create an `analysis_options.yaml` file at the root of your package or application 
and add either `include: package:deckweiss_lints/flutter.yaml` or 
`include: package:deckweiss_lints/lints.yaml` at the top of it.


[lints]: https://pub.dev/packages/lints
[flutter_lints]: https://pub.dev/packages/flutter_lints