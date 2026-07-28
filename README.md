# capability-time-now-days

Atomic authority package for `time/now-days`.

- imports: `#{:now-days}`
- effects: `#{:clock}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
