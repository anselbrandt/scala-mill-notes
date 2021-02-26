# scala-mill-notes

### Install 

```
brew install mill

or

sudo curl -L https://github.com/lihaoyi/mill/releases/download/0.9.5/0.9.5 > /usr/local/bin/mill && sudo chmod +x /usr/local/bin/mill
```

Check [mill](https://com-lihaoyi.github.io/mill/) for latest version.

`mill` only installs itself after being run the first time.

`mill version` to confirm installation.

### Run

Where `foo` is `main_class_name`

```
mill foo.compile

mill foo.run

mill foo.test

mill foo.assembly
```
