# Go

## Set Up
- Install Go
- Create a `workspace` directory
  - This directory will contain all of the `Go` things on the machine.
  - There are two folders `bin` and `src`. 
  - As most of my work will be source controlled on GitHub, my project directories will exist under `$GOPATH/src/github.com/ethan-arrowood/`.
- Set `$GOPATH` - this should be `$HOME/go`
  - On mac and ZSH add `export GOPATH=$HOME/go` to `~/.zshrc`
- Add `$GOPATH/bin` to `PATH` so the `go` project distributions can be run
    from anywhere on the machine

## How to compile and run code

Inside the working directory (under `src`) simply run `go install`.

If outside the working directory, must specify what to install i.e. `go install $GOPATH/src/github.com/ethan-arrowood/hello-go`