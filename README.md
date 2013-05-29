# CoffeeScript Compilation Experiment

## Run

```sh
nodebrew install-binary v0.10.0 # or v0.10
nodebrew use v0.10 # or v0.10
git clone https://github.com/kaosf/coffee-script-compilation-experiment
cd coffee-script-compilation-experiment
npm install

npm test #=>
#
# > coffee-script-compilation-experiment@0.0.0 test /your/path/to/coffee-compilation
# > node js/a; node js/b; node js/c/d
#
# this is a.
# this is b.
# this is c/d.
```
