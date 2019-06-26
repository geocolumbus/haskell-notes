# haskell-notes

## Install Haskell on the Mac

```
curl https://get-ghcup.haskell.org -sSf | sh
curl -sSL https://get.haskellstack.org/ | sh
```

Add ```export PATH=$PATH:/Users/georgecampbell/.local/bin``` to ```~/.bash_profile```

## Install from GitHub

git clone
cd haskell-notes
stack setup
stack build
stack exec haskell-notes-exe

## Build a Project from Scratch

stack new haskell-notes
cd haskell-notes
stack setup
stack build
stack exec haskell-notes-exe
```