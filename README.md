# Tail Recursion is its Own Reward 
A programming blog built with Hakyll

# Quickstart
## First run
```bash
cabal sandbox init
cabal insatll --only-dependencies
ghc --make -threaded site.hs
```

## Run locally
```bash
./site watch
```

## Deploy a new version
```bash
./site build && git subtree push --prefix _site origin gh-pages
```
