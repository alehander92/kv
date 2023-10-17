## kv

a simple toy key-value database, written in Haskell

### possible minimal initial scope:

* a simple lib-like internal API:
  * central data structures(hashmap? tree? others?)
  * put/get/delete methods
  * iteration/find?
* a simple CLI repl for interacting with toy dbs

### non-goals internally

but still interesting to research if it appears useful

* most of ACID
* concurrency
* more advanced operations
* many possible optimizations

### build

```bash
stack build
```

run with

```bash
stack run
# or
stack exec kv-exe
# the binary is probably in bin/ in this path:
stack path --local-install-root
```

### test

tests are not yet implemented, but we should run:

```bash
stack test
```

### license

BSD-3-Clause 

(seems to be by default with stack)

