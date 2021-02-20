# dot_functions
Repo of function files for use with .zshrc or .bashrc

## Usage
1.  Clone this repo into your home directroy.

2.  Rename the repo to .functions:
`mv dot_functions .aliases`

3.  Place the following block in your .zshrc file:
```
if [ -d ~/.functions ]
  then
    for file in `ls ~/.functions`
      do
        source ~/.functions/$file
    done
fi
```
