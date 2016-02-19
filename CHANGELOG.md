
# 0.1.10

* Updated to use `analyzer` `0.27.0`.
* Updated options processing to handle untyped maps (dart-lang/sdk#25126).

# 0.1.9

* Fix `type_annotate_public_apis` to properly handle getters/setters (#151; dart-lang/sdk#25092).

# 0.1.8

* Fix to protect against errors in linting invalid source (dart-lang/sdk#24910).
* Added `avoid_empty_else` lint rule (dart-lang/sdk#224936).

# 0.1.7

* Fix to `package_api_docs` (dart-lang/sdk#24947; #154).

# 0.1.6

* Fix to `package_prefixed_library_names` (dart-lang/sdk#24947; #154).

# 0.1.5

* Added `prefer_is_not_empty` lint rule (#143).
* Added `type_annotate_public_apis` lint rule (#24).
* Added `avoid_as` lint rule (#145).
* Fixed `non_constant_identifier_names` rule to special case underscore identifiers in callbacks.
* Fix to escape `_`s in callback type validation (addresses false positives in `always_specify_types`) (#147).

# 0.1.4

* Added `always_declare_return_types` lint rule (#146).
* Improved `always_specify_types` to detect missing types in declared identifiers and narrowed source range to the token.
* Added `implementation_imports` lint rule (#33).
* Test performance improvements.

# 0.1.3+5

* Added `always_specify_types` lint rule (#144).

# 0.1.3+4

* Fixed linter registry memory leaks.

# 0.1.3

* Fixed various options file parsing issues.

# 0.1.2

* Fixed false positives in `unnecessary_brace_in_string_interp` lint. Fix #112.

# 0.1.1

* Internal code and dependency constraint cleanup.

# 0.1.0

* Initial stable release.

# 0.0.2+1

* Added machine output option. Fix #69.
* Fixed resolution of files in `lib/` to use a `package:` URI. Fix #49.
* Tightened up `analyzer` package constraints.
* Fixed false positives in `one_member_abstracts` lint. Fix #64.

# 0.0.2

* Initial push to pub.