
# Clojure cli execution options


## Usage

### [clj-kondo](https://github.com/clj-kondo/clj-kondo "linting lib")

``` clojure
;; Basic usage
clj -M:lint --lint src

;;To print analysis data
clj -M:lint --lint src --config '{:output {:format :edn}, :analysis true}'
```

### [deps-new](https://github.com/seancorfield/deps-new)
```clojure
;; Create new application
clojure -Tnew app :name appname/core :target-dir appname

;; Create new libary
clojure -Tnew lib :name libname/core :target-dir libname
```
