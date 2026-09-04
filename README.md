 # Chenfeng Local Manifest

This repository contains the local manifest files for Xiaomi 14 Civi / Xiaomi Civi 4 Pro (chenfeng).

Use it to build your favourite custom rom.

<br/>

## Usage

From the root of an existing AOSP source tree, clone this repository into
the `.repo/local_manifests` directory:


Example lineage-23.2

```bash
git clone https://github.com/marcmyworld/chenfeng_manifest.git -b lineage-23.2 --depth=1 .repo/local_manifests
```

<br/>
After cloning the manifest, synchronize the source tree with the repo tool:

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$(nproc --all)

```
