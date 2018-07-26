## Hello

```bash
stack new Hello simple
stack build
stack exec hello
```

## GHC Version

```
stack exec -- ghc --version
```

## Compile file

```
stack ghc -- scripts/HelloWorld.hs
```

## Run file

```
stack exec -- runghc scripts/HelloWorld.hs
stack runghc -- scripts/HelloWorld.hs
```

## Package

stack scripts/Package.sh
