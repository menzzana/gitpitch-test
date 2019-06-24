## Test tables

| Computer | head1 | head2
| --- | --- | ---
| entry1 | entry2 | entry40

---

## Test font size

Original text

@snap[text-12]
size 12 text
@snapend

@snap[text-24]
size 24 text
@snapend

@snap[text-08]
size 8 text
@snapend

@snap[text-06]
size 6 text
@snapend

@snap[text-04]
size 4 text
@snapend

@snap[text-01]
size 1 text
@snapend

---

@snap[north]
@css[text-04](This works well one line and for multiple lines as well or only a single one?)
@snapend

---

* Install dependencies

```
build-essential
libssl-dev
uuid-dev
libgpgme11-dev
squashfs-tools
libseccomp-dev
wget
pkg-config
git
```

* Install go (version 1.12.6 2019-06-19)
* Install singularity from source (version 3.2.1-1 2019-06-18)

Follow instructions at https://www.sylabs.io/guides/3.2/user-guide/installation.html

Singularity cannot be installed on Mac or Windows, but can be used via VMs

---

* Install dependencies

```
build-essential
libssl-dev
uuid-dev
libgpgme11-dev
squashfs-tools
git
```

---
