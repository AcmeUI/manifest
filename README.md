# Acme UI

## Getting Started

To get started with the AcmeUI sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### 1. Initialize your local repository
```bash
repo init -u https://github.com/AcmeUI/manifest.git -b taffy
```

### 2. Sync up
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### 3. Clone your device sources repositories

### 4. Initialize the ROM environment with the envsetup.sh script
```bash
. build/envsetup.sh
```

### 5. Lunch your device
```bash
lunch acme_<$device_name>-<$buildtype>
```

### 6. Start compilation
```bash
mka acme
```

## Credits
- [LineageOS](https://github.com/LineageOS)
- [ArrowOS](https://github.com/ArrowOS)
- [Project-Kaleidoscope](https://github.com/Project-Kaleidoscope)
