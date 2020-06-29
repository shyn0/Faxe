# Faxe

> **Faxe - is the program to delete data from your device**

Faxe work as on termux, as on linux

## Necessary

**Need:**

> **root**(for linux, also for termux)

**or**

> **access to storage**(only for termux)

**Use** 'Settings>Apps>Termux>Permissions>Storage' and set to **true**

*but better to have a root..*

## Description

Write full paths in array in **Faxe/data/link/link.sh**

**For example:**

```
linkArray=("/storage/emulated/0/testDir/"
"/storage/emulated/0/testDir2/"
);
```

**P.s.** Faxe don't work when the directory have a double, triple(etc.) name

**For example:**

```
linkArray=("/storage/emulated/0/test Dir/"
"/storage/emulated/0/test Dir Second/"
);
```

## Installing

```
git clone https://github.com/KellyShyno/Faxe
cd Faxe
chmod -R a+rx *
./Faxe.sh
```

## About us

> **vk**: <https://vk.com/linuxkelly>

> **YouTube**: <https://www.youtube.com/channel/UC0FAZ36boaHKZgzbD3rMa_A>

**break a leg (#_#)**
