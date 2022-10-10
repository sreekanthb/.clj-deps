
## Aliases and Usage

### [clj-kondo](https://github.com/clj-kondo/clj-kondo "linting lib")

``` clojure
;; Basic usage
clj -M:lint --lint src

;;To print analysis data
clj -M:lint --lint src --config '{:output {:format :edn}, :analysis true}'
```

## Tools and Usage

### [tools.deps.alpha](https://github.com/clojure/tools.deps.alpha "clojure cli tools")
```clojure
;; tools.deps.alpha help
clojure -A:deps -Tnew help/[doc|dir]
```

### [deps-new](https://github.com/seancorfield/deps-new)
```clojure
;; Create new application
clojure -Tnew app :name appname/core :target-dir appname

;; Create new libary
clojure -Tnew lib :name libname/core :target-dir libname
```
