# para-tools
A collection of simple scripts for assisting with development on Linux platforms

These include:

| Tool                | Function                                                            |
|---------------------|---------------------------------------------------------------------|
| para-dir-hash       | Generates text hashes of directories that can be compared           |
| para-local-install  | A handy shortcut for installing a python script as a system command |


## Installing ##
The latest release is **v0.0.1-r1** [Git hash: ff5a81f]
<!-- markdown-link-check-disable-next-line -->
1. Download from: **[para-tools_0.0.1-1_all.deb](https://github.com/para-tools/para-tools/releases/download/v0.0.1-r1/para-tools_0.0.1-1_all.deb)**
2. Install with: **`sudo dpkg -i para-tools_0.0.1-1_all.deb`**

If you'd like to live life on the edge, you can do this with a single command:
```bash
deb_name="$(mktemp --suffix=.deb)" && \
wget      -O "$deb_name" https://github.com/para-tools/para-tools/releases/download/v0.0.1-r1/para-tools_0.0.1-1_all.deb && \
sudo dpkg -i "$deb_name"
```

## What does 'para' mean ? ##

* From Greek: "beside," "alongside," or "beyond" (eg: parallel)
* From Latin: "shield against" or "protection"   (eg: parachute, parasol).
* From Finnish Mythology: A house spirit who collects helpful titbits for the owner

It is the 'Finnish Mythology' usage that this archive is named after.


# More information #
 * Source code is available at **[github.com/para-tools/para-tools/(https://github.com/para-tools/para-tools/)**
 * Release history is available at **[github.com/para-tools/para-tools/releases](https://github.com/para-tools/para-tools/releases)**
