# haskell-notes

## PreReqs
```
brew install python3
brew install coreutils
```

## Install Haskell on the Mac
```
curl https://get-ghcup.haskell.org -sSf | sh
curl -sSL https://get.haskellstack.org/ | sh
```

Add ```export PATH=$PATH:/Users/georgecampbell/.local/bin``` to ```~/.bash_profile```

## Install from GitHub
```
git clone https://github.com/geocolumbus/haskell-notes.git
cd haskell-notes
stack setup
```

## Build and Run
```
stack build
stack exec haskell-notes-exe
```
