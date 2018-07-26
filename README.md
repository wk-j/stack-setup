## Hello

```bash
stack new Hello simple
stack build
stack exec hello
```

GHC Version

```
stack exec -- ghc --version
```

Run script

```
stack exec -- runghc scripts/HelloWorld.hs
stack runghc -- scripts/HelloWorld.hs
```

Add packages

```
stack scripts/Package.sh
```