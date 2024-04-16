## Repo Init ##
```bash
repo init -u https://github.com/OnePlus-12-Development/android_kernel_manifest.git -b lineage-21
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
## Building Kernel ##
```bash
./build.sh pineapple
```
