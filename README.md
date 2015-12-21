# Configuration for [atom](https://atom.io) text editor.

## Syncing installed packages

You can use the atom package manager (`apm`) to keep your installed packages
synchronized across several hosts. To dump a list of installed packages and
versions to a text file:

```
    apm list --installed --bare > packages.txt
```

Place `packages.txt` under version control. On your target machine, use the
file to install the same set of packages as follows:

```
    apm install --packages-file packages.txt
```
