# Uuid

Generate UUID V4.

## Installation

### Unix users (Linux, BSDs and MacOSX)

Unix users may download and install latest *uuid* release with command:

```bash
sh -c "$(curl https://sweetohm.net/dist/uuid/install)"
```

If *curl* is not installed on you system, you might run:

```bash
sh -c "$(wget -O - https://sweetohm.net/dist/uuid/install)"
```

**Note:** Some directories are protected, even as *root*, on **MacOSX** (since *El Capitan* release), thus you can't install *uuid* in */usr/bin* for instance.

### Binary package

Otherwise, you can download latest binary archive at <https://github.com/c4s4/uuid/releases>. Unzip the archive, put the binary of your platform somewhere in your *PATH* and rename it *uuid*.

## Usage

```bash
$ uuid
daeb9866-2af8-4a42-9afc-9daf4c999383
```

*Enjoy!*
