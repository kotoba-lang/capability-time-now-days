# capability-time-now-days

Atomic authority package for `time/now-days`.

- imports: `#{:now-days}`
- effects: `#{:clock}`
- default policy: `:autonomous`
- semantic definition CID: `bafyreigg7f4obntus3fdmeuxuhcatwg4ijkhyurjwh27kegrm2co2xuaxm`
- hash contract CID: `bafkreiflhj3fslsbh7okdas2fzlhmogai64x6p3lkla6gtr7berbp7ftvi`
- provider status: `contract-only`

The repository name is a discovery alias. The semantic definition CID
is the immutable import identity. Importing it does not grant runtime
authority: Tamaki must request it explicitly and Kototama must admit
the sealed envelope.

```sh
clojure -M:test
```
