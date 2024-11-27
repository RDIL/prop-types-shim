# @rdil/prop-types-shim

## What is this monstrosity?

This is a version of the `prop-types` package that has almost everything commented out.

You are hopefully asking "why??!" at this point. The answer is simple.

For codebases mid-transition to TypeScript, or codebases switching to a new build tool that doesn't support prop-types removal.

This package allows you to set a resolution for `prop-types`, so you don't have to change *any* of your existing code, but also don't have to deal with the pesky warnings.

No prop type checking, no (or, I guess, fewer) problems!

## Tests

Most of the tests have been deleted. But the remaining ones do ensure that it works as a shim.

## License

(@rdil/)prop-types(-shim) is [MIT licensed](./LICENSE).
