# argoneon-manjaro
argoneon.sh adapted for manjaro on RPI4

## How to use
1. Add to `/boot/config.txt`:
```
dtparam=i2c=on,i2s=on,spi=on
```

2. Add to or create `/etc/modules-load.d/raspberrypi.conf`:
```
i2c-dev
i2c-bcm2708
```

3. Reboot

4. Install
`curl https://github.com/DenisBY/argoneon-manjaro/raw/main/argoneon.sh | bash`
