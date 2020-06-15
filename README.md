# pispark

Setting up a Spark cluster on Raspberry Pi's


```bash
boot/
├── COPYING.linux
├── LICENCE.broadcom
├── bcm2708-rpi-b-plus.dtb
├── bcm2708-rpi-b.dtb
├── bcm2708-rpi-cm.dtb
├── bcm2708-rpi-zero-w.dtb
├── bcm2708-rpi-zero.dtb
├── bcm2709-rpi-2-b.dtb
├── bcm2710-rpi-2-b.dtb
├── bcm2710-rpi-3-b-plus.dtb
├── bcm2710-rpi-3-b.dtb
├── bcm2710-rpi-cm3.dtb
├── bcm2711-rpi-4-b.dtb
├── bootcode.bin
├── cmdline.txt
├── config.txt
├── fixup.dat
├── fixup4.dat
├── fixup4cd.dat
├── fixup4db.dat
├── fixup4x.dat
├── fixup_cd.dat
├── fixup_db.dat
├── fixup_x.dat
├── issue.txt
├── kernel.img
├── kernel7.img
├── kernel7l.img
├── kernel8.img
├── overlays
│   ├── README
│   ├── act-led.dtbo
│   ├── adau1977-adc.dtbo
│   ├── adau7002-simple.dtbo
│   ├── ads1015.dtbo
│   ├── ads1115.dtbo
│   ├── ads7846.dtbo
│   ├── adv7282m.dtbo
│   ├── adv728x-m.dtbo
│   ├── akkordion-iqdacplus.dtbo
│   ├── allo-boss-dac-pcm512x-audio.dtbo
│   ├── allo-digione.dtbo
│   ├── allo-katana-dac-audio.dtbo
│   ├── allo-piano-dac-pcm512x-audio.dtbo
│   ├── allo-piano-dac-plus-pcm512x-audio.dtbo
│   ├── anyspi.dtbo
│   ├── apds9960.dtbo
│   ├── applepi-dac.dtbo
│   ├── at86rf233.dtbo
│   ├── audioinjector-addons.dtbo
│   ├── audioinjector-ultra.dtbo
│   ├── audioinjector-wm8731-audio.dtbo
│   ├── audiosense-pi.dtbo
│   ├── audremap.dtbo
│   ├── balena-fin.dtbo
│   ├── bmp085_i2c-sensor.dtbo
│   ├── dht11.dtbo
│   ├── dionaudio-loco-v2.dtbo
│   ├── dionaudio-loco.dtbo
│   ├── disable-bt.dtbo
│   ├── disable-wifi.dtbo
│   ├── dpi18.dtbo
│   ├── dpi24.dtbo
│   ├── draws.dtbo
│   ├── dwc-otg.dtbo
│   ├── dwc2.dtbo
│   ├── enc28j60-spi2.dtbo
│   ├── enc28j60.dtbo
│   ├── exc3000.dtbo
│   ├── fe-pi-audio.dtbo
│   ├── goodix.dtbo
│   ├── googlevoicehat-soundcard.dtbo
│   ├── gpio-fan.dtbo
│   ├── gpio-ir-tx.dtbo
│   ├── gpio-ir.dtbo
│   ├── gpio-key.dtbo
│   ├── gpio-no-bank0-irq.dtbo
│   ├── gpio-no-irq.dtbo
│   ├── gpio-poweroff.dtbo
│   ├── gpio-shutdown.dtbo
│   ├── hd44780-lcd.dtbo
│   ├── hifiberry-amp.dtbo
│   ├── hifiberry-dac.dtbo
│   ├── hifiberry-dacplus.dtbo
│   ├── hifiberry-dacplusadc.dtbo
│   ├── hifiberry-dacplusadcpro.dtbo
│   ├── hifiberry-dacplusdsp.dtbo
│   ├── hifiberry-dacplushd.dtbo
│   ├── hifiberry-digi-pro.dtbo
│   ├── hifiberry-digi.dtbo
│   ├── hy28a.dtbo
│   ├── hy28b-2017.dtbo
│   ├── hy28b.dtbo
│   ├── i-sabre-q2m.dtbo
│   ├── i2c-bcm2708.dtbo
│   ├── i2c-gpio.dtbo
│   ├── i2c-mux.dtbo
│   ├── i2c-pwm-pca9685a.dtbo
│   ├── i2c-rtc-gpio.dtbo
│   ├── i2c-rtc.dtbo
│   ├── i2c-sensor.dtbo
│   ├── i2c0-bcm2708.dtbo
│   ├── i2c0.dtbo
│   ├── i2c1-bcm2708.dtbo
│   ├── i2c1.dtbo
│   ├── i2c3.dtbo
│   ├── i2c4.dtbo
│   ├── i2c5.dtbo
│   ├── i2c6.dtbo
│   ├── i2s-gpio28-31.dtbo
│   ├── ilitek251x.dtbo
│   ├── imx219.dtbo
│   ├── iqaudio-codec.dtbo
│   ├── iqaudio-dac.dtbo
│   ├── iqaudio-dacplus.dtbo
│   ├── iqaudio-digi-wm8804-audio.dtbo
│   ├── irs1125.dtbo
│   ├── jedec-spi-nor.dtbo
│   ├── justboom-both.dtbo
│   ├── justboom-dac.dtbo
│   ├── justboom-digi.dtbo
│   ├── ltc294x.dtbo
│   ├── max98357a.dtbo
│   ├── mbed-dac.dtbo
│   ├── mcp23017.dtbo
│   ├── mcp23s17.dtbo
│   ├── mcp2515-can0.dtbo
│   ├── mcp2515-can1.dtbo
│   ├── mcp3008.dtbo
│   ├── mcp3202.dtbo
│   ├── mcp342x.dtbo
│   ├── media-center.dtbo
│   ├── midi-uart0.dtbo
│   ├── midi-uart1.dtbo
│   ├── miniuart-bt.dtbo
│   ├── mmc.dtbo
│   ├── mpu6050.dtbo
│   ├── mz61581.dtbo
│   ├── ov5647.dtbo
│   ├── papirus.dtbo
│   ├── pi3-act-led.dtbo
│   ├── pi3-disable-bt.dtbo
│   ├── pi3-disable-wifi.dtbo
│   ├── pi3-miniuart-bt.dtbo
│   ├── pibell.dtbo
│   ├── piglow.dtbo
│   ├── piscreen.dtbo
│   ├── piscreen2r.dtbo
│   ├── pisound.dtbo
│   ├── pitft22.dtbo
│   ├── pitft28-capacitive.dtbo
│   ├── pitft28-resistive.dtbo
│   ├── pitft35-resistive.dtbo
│   ├── pps-gpio.dtbo
│   ├── pwm-2chan.dtbo
│   ├── pwm-ir-tx.dtbo
│   ├── pwm.dtbo
│   ├── qca7000.dtbo
│   ├── rotary-encoder.dtbo
│   ├── rpi-backlight.dtbo
│   ├── rpi-cirrus-wm5102.dtbo
│   ├── rpi-dac.dtbo
│   ├── rpi-display.dtbo
│   ├── rpi-ft5406.dtbo
│   ├── rpi-poe.dtbo
│   ├── rpi-proto.dtbo
│   ├── rpi-sense.dtbo
│   ├── rpi-tv.dtbo
│   ├── rra-digidac1-wm8741-audio.dtbo
│   ├── sc16is750-i2c.dtbo
│   ├── sc16is752-i2c.dtbo
│   ├── sc16is752-spi1.dtbo
│   ├── sdhost.dtbo
│   ├── sdio.dtbo
│   ├── sdtweak.dtbo
│   ├── smi-dev.dtbo
│   ├── smi-nand.dtbo
│   ├── smi.dtbo
│   ├── spi-gpio35-39.dtbo
│   ├── spi-gpio40-45.dtbo
│   ├── spi-rtc.dtbo
│   ├── spi0-cs.dtbo
│   ├── spi0-hw-cs.dtbo
│   ├── spi1-1cs.dtbo
│   ├── spi1-2cs.dtbo
│   ├── spi1-3cs.dtbo
│   ├── spi2-1cs.dtbo
│   ├── spi2-2cs.dtbo
│   ├── spi2-3cs.dtbo
│   ├── spi3-1cs.dtbo
│   ├── spi3-2cs.dtbo
│   ├── spi4-1cs.dtbo
│   ├── spi4-2cs.dtbo
│   ├── spi5-1cs.dtbo
│   ├── spi5-2cs.dtbo
│   ├── spi6-1cs.dtbo
│   ├── spi6-2cs.dtbo
│   ├── ssd1306.dtbo
│   ├── superaudioboard.dtbo
│   ├── sx150x.dtbo
│   ├── tc358743-audio.dtbo
│   ├── tc358743.dtbo
│   ├── tinylcd35.dtbo
│   ├── tpm-slb9670.dtbo
│   ├── uart0.dtbo
│   ├── uart1.dtbo
│   ├── uart2.dtbo
│   ├── uart3.dtbo
│   ├── uart4.dtbo
│   ├── uart5.dtbo
│   ├── udrc.dtbo
│   ├── upstream.dtbo
│   ├── vc4-fkms-v3d.dtbo
│   ├── vc4-kms-kippah-7inch.dtbo
│   ├── vc4-kms-v3d.dtbo
│   ├── vga666.dtbo
│   ├── w1-gpio-pullup.dtbo
│   ├── w1-gpio.dtbo
│   ├── w5500.dtbo
│   └── wittypi.dtbo
├── start.elf
├── start4.elf
├── start4cd.elf
├── start4db.elf
├── start4x.elf
├── start_cd.elf
├── start_db.elf
└── start_x.elf

1 directory, 227 files

```

```bash
COPYING.linux
LICENCE.broadcom
bcm2708-rpi-b-plus.dtb
bcm2708-rpi-b.dtb
bcm2708-rpi-cm.dtb
bcm2708-rpi-zero-w.dtb
bcm2708-rpi-zero.dtb
bcm2709-rpi-2-b.dtb
bcm2710-rpi-2-b.dtb
bcm2710-rpi-3-b-plus.dtb
bcm2710-rpi-3-b.dtb
bcm2710-rpi-cm3.dtb
bcm2711-rpi-4-b.dtb
bootcode.bin
cmdline.txt
config.txt
fixup.dat
fixup4.dat
fixup4cd.dat
fixup4db.dat
fixup4x.dat
fixup_cd.dat
fixup_db.dat
fixup_x.dat
issue.txt
kernel.img
kernel7.img
kernel7l.img
kernel8.img
overlays/
start.elf
start4.elf
start4cd.elf
start4db.elf
start4x.elf
start_cd.elf
start_db.elf
start_x.elf
```


```bash
-rwxrwxrwx 1 tallamjr staff        0 May  2 18:33 ssh

```

```bash
# Example static IP configuration:
interface eth0
static ip_address=192.168.0.101/24
#static ip6_address=fd51:42f8:caae:d92e::ff/64
#static routers=192.168.0.1
#static domain_name_servers=192.168.0.1 8.8.8.8 fd51:42f8:caae:d92e::1

```

```bash
ssh pi@raspberrypi.local
```

```bash
sudo raspi-config
```

```bash
sudo apt-get update

sudo apt-get upgrade
```

```bash
sudo apt-get install nmap
```

```bash
ssh -vvv pi@rasp0.local
```

#### LINKS

Install Apache Spark on EC2 instances
https://maelfabien.github.io/bigdata/Spark/#

Connect from a Mac
https://www.dexterindustries.com/getting-started/using-the-pi/connect-to-your-raspberry-pi-from-a-mac/

How to Assign Static IP Address on Raspberry Pi
https://accidentaltechnologist.com/raspberry-pi/how-to-assign-static-ip-address-on-raspberry-pi/

Building a Raspberry Pi Hadoop / Spark Cluster
https://dev.to/awwsmm/building-a-raspberry-pi-hadoop-spark-cluster-8b2#hadoopspark

How (and Why) to Assign the .local Domain to Your Raspberry Pi
https://www.howtogeek.com/167190/how-and-why-to-assign-the-.local-domain-to-your-raspberry-pi/

Setting up SSH Keys on the Raspberry Pi
https://www.raspberrypi-spy.co.uk/2019/02/setting-up-ssh-keys-on-the-raspberry-pi/

Make your very own Kubernetes cluster from a Raspberry PI
https://medium.com/nycdev/k8s-on-pi-9cc14843d43
