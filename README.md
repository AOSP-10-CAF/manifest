# Android 10 for MSM Project

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/AOSP-10-CAF/manifest -b 10

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
