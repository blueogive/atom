# Configuration for [atom](https://atom.io) text editor

## Syncing configuration settings

I keep my atom configuration settings in a public github repository. Atom
expects to find these settings in a directory named `.atom` in your home
directory (i.e., `C:\Users\<username>` on Windows or `/home/<username>` on
Linux or `/Users/<username>` on Mac OS X. You can clone my atom configuration
with this sequence of commands:

```
    cd <path-to-home-directory>
    git clone https://github.com/blueogive/atom .atom
```

## Syncing installed packages

You can use the atom package manager (`apm`) to keep your installed packages
synchronized across several hosts. Github users can 'star' atom packages to
signal to others which packages they favor. To outfit atom with the set of
packages I favor, issue this command:

```
    apm stars -i -u blueogive
```
