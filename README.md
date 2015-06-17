# named-regexp-debs
Build Debian Package for Named capture groups for Java regular expressions (v0.2.3)

**Instructions**

Inside of the debs folder

**Gets orig source code**

```
debian/rules get-orig-source
```

**Check dependencies**

```
dpkg-checkbuilddeps
```

**Build source package**

```
debuild -S -nc -uc -us
```

**Tested**

```
Debian wheezy
```
```
Debian jessie
```

