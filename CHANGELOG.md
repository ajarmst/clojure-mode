# Changelog

## master (unreleased)

## 3.0.0 (2/9/2014)

### New features

* Added font-locking for namespaces and namespace aliases.
* Added font-locking for character literals.
* Added font-locking for constants.
* Added font-locking for dynamic vars.
* Added font-locking for `cljx`.
* Various docstring filling improvements.
* Introduced additional faces for keyword literals, character literals and
interop method invocations.

### Changes

* Emacs 24.1 is required.
* Removed deprecated `clojure-font-lock-comment-sexp`.
* Renamed `clojure-mode-font-lock-setup` to `clojure-font-lock-setup`.

### Bugs fixed

* Properly font-lock docstrings regardless of the presence of metadata or type hints.