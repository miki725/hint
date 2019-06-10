# Devhints.io CLI

[devhints.io](https://devhints.io/) CLI,
sort of similar to [tldr.sh](https://tldr.sh/).

Features:

* shows hints in `less`
* syntax highlights markdown via `pygmentize`
* allows to search for hints via fzf

## Install

```
brew install miki725/brews/hint
```

## Usage

Hints can be directly referenced:

```
hint pacman
```

Alternatively hints can be searched via `fzf`:

```
hint
```

Hints themselves are cloned from [github](https://github.com/rstacruz/cheatsheets)
hence once in a while they might need to be updated via:

```
hint --update
```
