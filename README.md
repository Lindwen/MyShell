# MyShell
A place where you can find all my configurations 

## [Arsenal](https://github.com/Orange-Cyberdefense/arsenal)

### Install

```bash
python3 -m pip install arsenal-cli
```

### Configuration

Remove all default cheats

```bash
mv ~.local/lib/python3.X/site-packages/arsenal/data/cheats ~.local/lib/python3.X/site-packages/arsenal/data/cheats_OLD
```

Add Alias to bash profile

```bash
vi .bash_aliases
#--> alias a='arsenal'
```

Add new cheat files

```bash
mkdir ~.cheats
```

Template files can be found on the [arsenal](https://github.com/Orange-Cyberdefense/arsenal/tree/master/arsenal/data/cheats) repo