# Tail Recursion is its Own Reward 
A programming blog built with Hakyll

# Quickstart
## Setup
```bash
cabal sandbox init
cabal insatll --only-dependencies
ghc --make -threaded site.hs
```

## Run locally
```bash
./site watch
```
Navigate to `http://localhost:8000` in your browser

## Deploy a new version
```bash
./site build && git subtree push --prefix _site origin gh-pages
```

# Contribution
1. Fork the repo
2. Write your post
3. Submit a pull request

# Errata
- [More info on Hakyll](http://jaspervdj.be/hakyll)
