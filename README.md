# MakeVendor
I got tired of manually extracting zips to make treble "only-vendor" flashables for kenzo, so here it is

# Setup and run

```
sudo apt install php7.2 php7.2-zip
git clone https://github.com/AryToNeX/MakeVendor
cd MakeVendor
cp /path/to/treble-rom.zip rom.zip
chmod +x MakeVendor
./MakeVendor -i rom.zip -o vendor.zip
```

# If you don't have kenzo, just edit the `new-updater-script` with one that fits your needs.
