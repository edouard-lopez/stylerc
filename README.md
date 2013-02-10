# stylerc

## Description

Define some variables and function to help format output.

## Usage

First, you need to define a global variable in your `~/.bashrc` or `~/.zshrc` as follow:

    export STYLERC="$HOME/path/to/stylerc"

Then you need to include/source this file in your script to be able to use the variables:

    source "$STYLERC" # include style

Finally you can call variables and function:

    printf "normal text %s\n" "$(_error "caused by whatever")"