# cljsjs/{package}

[![Clojars Project](https://img.shields.io/clojars/v/cljsjs/{package}.svg)](https://clojars.org/cljsjs/{package})

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the Clojurescript compiler. After adding the above dependency to your project
you can require the packaged library like:

```clojure
(ns application.core
  (:require [cljsjs.{package}]))
```

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
