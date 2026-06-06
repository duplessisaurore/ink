
<h1 align="center">Ink</h1>

<div align="center">
ᝰ🖋️ˎˊ˗.𖥔 ݁ ˖
</div>
<div align="center">
  <strong>My Arch Linux user repository</strong>
</div>
<div align="center">
  An Arch Linux user repository containing my personal software.
</div>


## 📜 Table of Contents
- [<code>📖 Getting Started</code>](#getting-started)
- [<code>📦 Packages</code>](#packages)
- [<code>🧾 License</code>](#license)

<a name="getting-started"></a>
## 📖 Getting Started 

Add this user repository to Arch Linux by adding these lines to ``/etc/pacman.conf`` as described in **https://wiki.archlinux.org/title/Pacman#Repositories_and_mirrors**. 

Note that the packages and package list are unsigned so ``SigLevel = Optional`` must be used, ensure the server is used over https to prevent any MITM attacks.

```
[ink]
SigLevel = Optional
Server = https://ink.sudlicht.com
```

<a name="packages"></a>
## 📦 Packages

All package names are prefixed with ``ink-`` to differentiate them from the existing software. The binary installed will not have these ``ink-`` prefixes.

### ``typewriter``

A <code>TOML</code> file-based configuration file management program for centralising configuration.

https://github.com/duplessisaurore/typewriter

### ``blueprint``

A <code>TOML</code> file-based declarative package manager wrapper.

https://github.com/duplessisaurore/blueprint

### ``lepton3``

A bytecode virtual machine for the `Fermion3` language.

https://github.com/duplessisaurore/lepton3

### ``quark3``

A textual assembly language that compiles to `Lepton3` bytecode. 

https://github.com/duplessisaurore/quark3

<a name="license"></a>
## 🧾 License

This repository/``ink`` is under the AGPLv3 license. view it in the ``LICENSE`` file in the root directory of the repository.

-------------

[Ink Authored/Created by Aurore du Plessis](https://github.com/duplessisaurore/ink)

Love for everyone 💛 
