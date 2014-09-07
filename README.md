# chloey

A minimal IRC bot in Clojure.

## Usage

``lein run``

## Simple Factoid Storage/Retrieval

### How to store a factoid

Format: ``chloey: <subject> is <factoid>``

e.g.

```
[21:37] <microamp> chloey: everything is awesome
```

### How to retrieve a factoid

Format: ``<subject>?``

e.g.
```
[21:53] <microamp> everything?
[21:53] <chloey> microamp said everything is awesome
```

## License

Copyright © 2014 James Nah

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
