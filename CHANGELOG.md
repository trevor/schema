## 0.1.8
 * Works with advanced compilation in cljs (at least sometimes)

## 0.1.7
 * More small bugfixes
 * Better validation error messages in cljs

## 0.1.6
 * Minor bugfixes (thanks various contributors)
 * Extend schema protocol to regex (thanks [AlexBaranosky](https://github.com/AlexBaranosky)).
 * Add `:never-validate` meta option

## 0.1.5
 * Fix regression in primitive handling introduced in 0.1.4

## 0.1.4
 * Added Regex, Inst, and Uuid as primitive schema types (thanks [jwhitlark](https://github.com/jwhitlark))
 * Add annotated arglists to functions defined with `s/defn` (thanks [danielneal](https://github.com/danielneal))
 * Add `set-fn-validation!` to schema.core, to globally turn validation on or off.
 * Add `:always-validate` metadata on fn/defn name to unconditionally use validation.

## 0.1.3
 * Fix compatibility with Clojurescript 1889 (removal of format)

## 0.1.2
 * Validate returns the value on success
 * Sequence schemas only match sequential? things, to match map and set
 * Implementation of `defschema` puts name in metadata, rather than generating named schema
 * Improved error messages and stack traces for `s/defn`

## 0.1.1
 * Bugfix: with-fn-validation persisting after Exception

## 0.1.0
 * Initial release
