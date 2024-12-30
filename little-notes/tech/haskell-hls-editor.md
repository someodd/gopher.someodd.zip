You may notice that ensuring Haskell Language Server plays nice with, say, VSCode.

Two things: you need to tell either a cabal config your your stack.yaml to enable `haddock` for better tooltips.

You also probably want an hie.yaml.

For Stack `hie.yaml`:

```
cradle:
  stack:

```

for cabal:

```
cradle:
  cabal:

```
