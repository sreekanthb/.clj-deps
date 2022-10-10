
## Aliases and Usage

### clj-kondo

``` clojure
;; Basic usage
clj -M:lint --lint src

;;To print analysis data
clj -M:lint --lint src --config '{:output {:format :edn}, :analysis true}'
```

## Tools and Usage

### tools.deps.alpha
```clojure
;; tools.deps.alpha help
clojure -A:deps -Tnew help/doc[dir]
```

### deps-new
```clojure
;; Create new application
clojure -Tnew app :name appname/core :target-dir appname

;; Create new libary
clojure -Tnew lib :name libname/core :target-dir libname
```
