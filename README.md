# siemens-rip – Extract images from Siemens mobile fullflash

`siemens-rip` is a command‑line tool that extracts all images from a Siemens mobile phone fullflash dump (SG, NSG, ELKA).

## Building
The tool depends on [`libsimg`](https://github.com/siemens-mobile-hacks/libsimg) (Siemens Image Library).
For the build to work, `libsimg` must be placed **next to** the `siemens-rip` source folder.
```bash
mkdir build && cd build
cmake ..
make
```

## Usage
```bash
./siemens-rip fullflash.bin
```
