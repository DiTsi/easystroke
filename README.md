# jumpapp for Void Linux

Template and scripts for building [easystroke](https://github.com/thjaeger/easystroke)

Scripts use [official way](https://github.com/void-linux/void-packages/blob/master/README.md) for building custom packages. It's taking up about 1Gb of space for void-packages. Just remove it after install.

## Build and install
```bash
git clone https://github.com/DiTsi/easystroke.git
cd easystroke
./build.sh
./install.sh1
```

## Remove
```bash
sudo xbps-remove -R easystroke
```
