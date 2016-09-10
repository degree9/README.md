# boot-{taskname}
[![Clojars Project](https://img.shields.io/clojars/v/degree9/{taskname}.svg)](https://clojars.org/degree9/{taskname})
[![CircleCI](https://circleci.com/gh/degree9/{taskname}.svg?style=svg)](https://circleci.com/gh/degree9/{taskname})
[![Dependencies Status](https://jarkeeper.com/degree9/{taskname}/status.svg)](https://jarkeeper.com/degree9/{taskname})
[![Downloads](https://jarkeeper.com/degree9/{taskname}/downloads.svg)](https://jarkeeper.com/degree9/{taskname})

{description} for [boot-clj][1].

* {tasklist}

> The following outlines basic usage of the task, extensive testing has not been done.
> Please submit issues and pull requests!

## Usage

Add `{taskname}` to your `build.boot` dependencies and `require` the namespace:

```clj
(set-env! :dependencies '[[degree9/{taskname} "X.Y.Z" :scope "test"]])
(require '[degree9.{taskname} :refer :all])
```

{demo-description}

```bash
boot {task} {args}
```

Use in a wrapper task:

```clojure
(boot/deftask mytask
  ""
  [...]
  (let [...]
    (comp
      {task-fn})))
```

##Task Options

{options-description}

```clojure
{options}
```

{options-notes}

[1]: https://github.com/boot-clj/boot
