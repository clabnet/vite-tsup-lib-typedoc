# vite-tsup-lib-typedoc

This is a `vite` boilerplate project. Primarily, for rapid `ts` supported modules for publishing onto `npm`.

## Testing with Vitest

Run `pnpm test:run` or `pnpm test:coverage` to produce code coverage report.

The code coverage report will indicate, if all test cases are 100% covered, flawed logic and so on.

## Running `vite`

Run `pnpm dev` to open `index.html` via `http://localhost:3000`.

It contains some quick links, to the `stats.html` and coverage `index.html` files.

## Publishing

And when ready to publish to `npm`:

```
npm login
npm publish
```

## Credits
This is a fork of vite-vanilla-ts-module. I have enhanced it adding tsup as fast build compiler. Typedoc and Vite are also included. Removed husky.