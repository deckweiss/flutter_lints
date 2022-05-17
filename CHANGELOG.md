## 1.0.0+1
- fix: copy rules form `very_good_analysis` instead of including it.
- feat: remove [package_api_docs](https://dart-lang.github.io/linter/lints/package_api_docs.html)

## 1.0.0
- feat: include `very_good_analysis` as base ruleset
- feat: exclude rules:
    - [cascade_invocations](https://dart-lang.github.io/linter/lints/cascade_invocations.html)
    - [one_member_abstracts](https://dart-lang.github.io/linter/lints/one_member_abstracts.html)
    - [public_member_api_docs](https://dart-lang.github.io/linter/lints/public_member_api_docs.html)
- feat: add rules:
    - [avoid_multiple_declarations_per_line](https://dart-lang.github.io/linter/lints/avoid_multiple_declarations_per_line.html)
- feat: exclude files:
    - `/**.g.dart`
    - `/**.freezed.dart`