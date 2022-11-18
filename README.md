# astralUI #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/astralui-project/manifest -b thirteen

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

