## 0.4.0 (2019-08-20)

- **Breaking**:
    - Requires Clojure 1.9 (for spec)
- Sass4clj now contains main namespace for `clj` use
- Sass4clj new has `sass4clj.api` namespace with easy to use `start` and `stop` functions
- Add [Integrant](https://github.com/weavejester/integrant) namespace `sass4clj.integrant` namespace
- Add [Component](https://github.com/stuartsierra/component) namespace `sass4clj.component` namespace
- Use [Hawk](https://github.com/wkf/hawk/) for watching for file changes, this should work better on OS X
- Support Webpack style import paths, which support starting the path with `~`
when referring to Node packages.
- Add `inputs` option which can be used to select main files

**[compare](https://github.com/Deraen/sass4clj/compare/0.3.1...0.4.0)**

## 0.3.1 (8.3.2017)

**[compare](https://github.com/Deraen/sass4clj/compare/0.3.0...0.3.1)**

- Fixed a bad macro in Leiningen plugin which broke less4clj with Clojure 1.9-alpha14

## 0.3.0 (18.10.2016)

**[compare](https://github.com/Deraen/sass4clj/compare/0.2.1...0.3.0)**

- Run tests on Windows CI
- Update to latest jsass ([#6](https://github.com/Deraen/sass4clj/pull/6))
- Supports source maps ([#1](https://github.com/Deraen/sass4clj/pull/1))
- Support raw css imports ([#14](https://github.com/Deraen/sass4clj/pull/14))

## 0.2.1 (22.2.2016)

**[compare](https://github.com/Deraen/sass4clj/compare/0.2.0...0.2.1)**

- Fixed the documentation about main files
    - Main files don't need to end with `.main.ext`
    - Main files are the files not starting with `_`
- Fix URI construction on Windows ([#7](https://github.com/Deraen/sass4clj/pull/7))

## 0.2.0 (25.12.2015)

- Synchronized versions between all packages
- Boot and Lein packages are now maintained in sass4clj repository

## 0.1.1 (27.9.2015)

- Fixed local file imports

## 0.1.0 (26.9.2015)
