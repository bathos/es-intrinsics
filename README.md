# es-intrinsics

Exports a map of the
[named intrinsic objects](https://tc39.github.io/ecma262/#sec-well-known-intrinsic-objects)
of an EcmaScript realm. Presumes an ES2015 environment at minimum, but is
forgiving for > ES2015; relies on access through the global object, so if this
is to be mutated, it must run first to capture the references.
