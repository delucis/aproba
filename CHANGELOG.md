3.0.0
  * ***~ Breaking ~*** Add support for ES2015 types: `Map`, `WeakMap`, `Set`, `WeakSet`, and `Symbol`. A schema of `'O'` will now reject if passed map or set instances (although, like arrays, they are `typeof == 'object'` and previously would have been succesfully validated)

2.0.0
  * Drop support for 0.10 and 0.12. They haven't been in travis but still,
    since we _know_ we'll break with them now it's only polite to do a
    major bump.
