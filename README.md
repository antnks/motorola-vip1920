# motorola-vip1920
Hacking Telia tv box Motorola VIP1920

# Telia AES key

Symmetric AES-256-ECB key used to encrypt firmware:
```
5acb889e1cb69263ee0220241a4b21a4ef6df5459e3425b672b0ea5cb5ba340f
```

# Telia firmware boot log

```

Booting...
System memory: 128 MB

Video memory: 32 MB

Using Slot 1

Unpacking Image ...Done

Linux version 2.6.17.14-sh (erik@xenalinux) (gcc version 3.4.3 (STMicroelectronics Special) [build Feb 5 2007]) #1 Thu Sep 11 14:28:31 CEST 2008
STMicroelectronics STb7100 Reference board initialisation
LMI SYS setup, fixing blue dots
LMI VID setup, fixing blue dots
STb7109 version 3.x
Built 1 zonelists
Kernel command line: console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x00070000@0x00390000(FFS),0x00390000@0x0(Raw) ramtopaddress=0xAC000000 systemmemsize=131072 videomemsize=32768 rbl=2 rbl_mode=1 dbl=1 fw=2.26
PID hash table entries: 512 (order: 9, 2048 bytes)
Using tmu for system timer
Console: colour dummy device 80x25
Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
Memory: 112056k/120832k available (1580k kernel code, 8612k reserved, 280k data, 76k init)
PVR=04061100 CVR=30480000 PRR=00009300
I-cache : n_ways=2 n_sets=256 way_incr=8192
I-cache : entry_mask=0x00001fe0 alias_mask=0x00001000 n_aliases=2
D-cache : n_ways=2 n_sets=512 way_incr=16384
D-cache : entry_mask=0x00003fe0 alias_mask=0x00003000 n_aliases=4
Mount-cache hash table entries: 512
CPU: STb710x
checking if image is initramfs... it is
Overmounted tmpfs
Freeing initrd memory: 906k freed
NET: Registered protocol family 16
Generic PHY: Registered new driver
DMA: Registering DMA API.
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 4096 (order: 2, 16384 bytes)
TCP bind hash table entries: 2048 (order: 1, 8192 bytes)
TCP: Hash tables configured (established 4096 bind 2048)
TCP reno registered
bigphysarea: Allocated 1152 pages at 0x842ed000.
JFFS2 version 2.2. (C) 2001-2003 Red Hat, Inc.
io scheduler noop registered
io scheduler anticipatory registered (default)
STPIO layer initialised
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
STMicroelectronics ASC driver initialized
ttyAS0 at MMIO 0xb8031000 (irq = 122) is a asc
DMA: Registering ST40 STB710x FDMAC handler (5 channels).
STMicroelectronics - Coprocessors st231 Init
st-coprocessor-0: No RAM reserved
st231-0 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
st-coprocessor-1: No RAM reserved
st231-1 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
ST Cryptocore Version 1.5b
RAMDISK driver initialized: 1 RAM disks of 262144K size 1024 blocksize
LAN8700: Registered new driver
STMMAC driver:
	platform registration... <6>done!
	no valid MAC address; please, set using ifconfig or nwhwconfig!
STMMAC MII Bus: probed
Registrating STMMAC reboot notifier
Generic ST boards onboard flash device: 0x00400000 (4.0MB) at 0x00000000
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
 Intel/Sharp Extended Query Table at 0x0035
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x00390000-0x00400000 : "FFS"
0x00000000-0x00390000 : "Raw"
i2c /dev entries driver
i2c_st40_pio: ST40 PIO based I2C Driver
i2c_st40_pio: allocated pin (2,0) for scl (0x841f4a24)
i2c_st40_pio: allocated pin (2,1) for sda (0x841f4a34)
i2c_st40_pio: allocated pin (4,0) for scl (0x841f4b24)
i2c_st40_pio: allocated pin (4,1) for sda (0x841f4b34)
i2c_st40_pio bus 0: SCL=PIO2[0], SDA=PIO2[1]
i2c_st40_pio bus 1: SCL=PIO4[0], SDA=PIO4[1]
fan_ctrl: Activating fan monitoring
TCP bic registered
NET: Registered protocol family 1
NET: Registered protocol family 17
Freeing unused kernel memory: 76k freed
gpio: module license 'Proprietary' taints kernel.
-----------------------------------------------------
Init started
-----------------------------------------------------
Mounting filesystems
Verifying system integrity...
System integrity is intact
Mounting the flash file system
Reading configuration parameters
Running on Motorola VIP1920-9T with Firmware version 2.26
Using Vendor Class Id Motorola_VIP1920-9T
Using Bootcast Id motorola-vip1920-9t
Using SAP Id motorola.vip1920-9t
kb driver loaded
LEDs only mounted
Initialized display. Type is 0
Front_Paneldev: registered device with major 122
front_panel driver loaded
Initializing video
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Releasing font
Deinitialize Free Type Library
Graphics device closed.
Entering video active mode
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Could not open /tmp/splash.bmp
Mounting flash memory
NAND device: Manufacturer ID: 0x20, Chip ID: 0x75 (ST Micro NAND 32MiB 3,3V 8-bit)
Scanning device for bad blocks
Bad eraseblock 258 at 0x00408000
Creating 1 MTD partitions on "NAND 32MiB 3,3V 8-bit":
0x00000000-0x02000000 : "KREATEL NANDflash partition"
yaffs Sep 11 2008 14:28:35 Installing. 
yaffs: dev is 32505858 name is "mtdblock2"
yaffs: Attempting MTD mount on 31.2, "mtdblock2"
block 259 is bad
PHY: 0:1f - Link is Up - 100/Full
input: Kreatel IR-keyboard/remote as /class/input/input0
ir_kreatel: Enable interrupt
IR driver loaded
No valid splash image in local storage
Bringing up the network
Reading link status...
-> Link is up
Using DHCP
IP-Config: eth0 hardware address 00:02:9b:22:b7:20 mtu 1500 DHCP
IP-Config: eth0 complete (from 192.168.99.9):
 address: 192.168.99.109   broadcast: 192.168.99.255   netmask: 255.255.255.0   
 gateway: 192.168.99.9     dns0     : 192.168.99.9     dns1   : 0.0.0.0         
 nfsserver: 192.168.99.9
 nfspath: 

Download parameters:
  Splash boot order: 313
  Kernel boot order: 313
  Bootcast address : 224.2.2.2:22222
  Sap address      : 224.2.127.254:9875

***** Loading splash image *****

Using Local Storage
LS: No valid splash image available.

Using Bootcast
BC: Info download attempt 1 of 1
Loading control file motorola-vip1920-9t from 224.2.2.2:22222
Connection timeout.
Child process (/usr/bin/multicast) exited with failure code 1!
BC: Failed!

Using Local Storage
LS: No valid splash image available.

Unable to successfully display a splash image. Skipping splash!

***** Loading kernel image *****

Using Local Storage
LS: Image found
Retrieving network kernel version from Bootcast...
Loading control file motorola-vip1920-9t from 224.2.2.2:22222
Connection timeout.
Child process (/usr/bin/multicast) exited with failure code 1!
Using kernel image in flash
Copying 19403311 bytes...
Verifying image...
Uncompressing image...
Unmounting nand flash...
save entry: isCheckpointed 0
checkpoint byte count 0
save exit: isCheckpointed 0
Unloading IR module...
Loading new kernel...
Initrd at 0xb0001000, length 18184167 bytes
Command line (356 bytes):  console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x70000@0x390000(FFS),0x390000@0x0(Raw) ip=192.168.99.109::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:22:B7:20 rbl=2 rbl_mode=1 dbl=1 bch=224.2.2.2:22222 ramtopaddress=0xac000000 systemmemsize=131072 videomemsize=32768 serverid=192.168.99.9 last_key=none videomode=PAL,RGB
Kernel loaded successfully!
Disabling FDMA
Shuting down STMMAC TX and RX DMA
Starting new kernel...
kexec information
  segment[0]: 0x84700000 - 0x84972000 (0x00272000)
  segment[1]: 0xb0001000 - 0xb1159000 (0x01158000)
  start     : 0x84701000

Entering Space Enhanced Mode (32 bit)
Running 32 bit Mode
Linux version 2.6.23.17 (dailybuild@teaninich) (gcc version 4.2.1 20070719 (experimental) (STMicroelectronics Special) [build Nov 25 2008]) #1 PREEMPT Mon Apr 27 18:21:09 CEST 2009
Booting machvec: STb7100 Reference board
Reserve 0x46063000 - 0x47fff000 (0x1f9c000) for STAVMEM
Node 0: start_pfn = 0x40000, low = 0x48000
Zone PFN ranges:
  Normal     262144 ->   294912
Movable zone start PFN for each node
early_node_map[1] active PFN ranges
    0:   262144 ->   294912
Motorola VIP19xx board initialisation
LMI SYS setup, fixing blue dots
LMI VID setup, fixing blue dots
STx7109 version 3.x
Chip version 3.4
Built 1 zonelists in Zone order.  Total pages: 32512
Kernel command line:  console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x70000@0x390000(FFS),0x390000@0x0(Raw) ip=192.168.99.109::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:22:B7:20 rbl=2 rbl_mode=1 dbl=1 bch=224.2.2.2:22222 ramtopaddress=0xac000000 systemmemsize=131072 videomemsize=32768 serverid=192.168.99.9 last_key=none videomode=PAL,RGB
Kernel has NOT DVR version 5 support
Kernel has DVB support
BPA2 (bigphysarea) @ 0x40802000 size 0x001ccfff
PID hash table entries: 512 (order: 9, 2048 bytes)
Using tmu for system timer
Using 16.594 MHz high precision timer.
Console: colour dummy device 80x25
console [ttyAS0] enabled
Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
Memory: 85816k/131072k available (1942k kernel code, 446k data, 104k init)
PVR=04061100 CVR=30480000 PRR=00009300
I-cache : n_ways=2 n_sets=256 way_incr=8192
I-cache : entry_mask=0x00001fe0 alias_mask=0x00001000 n_aliases=2
D-cache : n_ways=2 n_sets=512 way_incr=16384
D-cache : entry_mask=0x00003fe0 alias_mask=0x00003000 n_aliases=4
Mount-cache hash table entries: 512
CPU: STb7109
NET: Registered protocol family 16
Generic PHY: Registered new driver
Time: SuperH clocksource has been installed.
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 4096 (order: 3, 32768 bytes)
TCP bind hash table entries: 4096 (order: 2, 16384 bytes)
TCP: Hash tables configured (established 4096 bind 4096)
TCP reno registered
Unpacking initramfs...<6>Overmounted tmpfs
 done
JFFS2 version 2.2. © 2001-2006 Red Hat, Inc.
io scheduler noop registered
io scheduler anticipatory registered (default)
Kboxdev: registered device with major 120
Kboxdev: ramtopaddress: 0x48000000, videomemaddress: 0x60000000
STMicroelectronics ASC driver initialized
stasc.0: ttyAS0 at MMIO 0x18031000 (irq = 122) is a stasc
stasc.1: ttyAS1 at MMIO 0x18032000 (irq = 121) is a stasc
SMSC LAN8700: Registered new driver
STMMAC driver:
	platform registration... <6>done!
	MAC 10/100
	no valid MAC address; please, set using ifconfig or nwhwconfig!
STMMAC MII Bus: probed
nwhw_config: (eth0) setting mac address: 00:02:9B:22:B7:20
VIP19xx onboard flash device
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
 Intel/Sharp Extended Query Table at 0x0035
Using word write for ST M28WXX0 FLASH
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x00390000-0x00400000 : "FFS"
0x00000000-0x00390000 : "Raw"
mice: PS/2 mouse device common for all mice
i2c /dev entries driver
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
STMicroelectronics - Coprocessors st231 Init
st-coprocessor-0: No RAM reserved
st231.0 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
st-coprocessor-1: No RAM reserved
st231.1 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
stm_rng hardware driver 1.0 configured
TCP cubic registered
NET: Registered protocol family 1
NET: Registered protocol family 17
IP-Config: Complete:
      device=eth0, addr=192.168.99.109, mask=255.255.255.0, gw=192.168.99.9,
     host=192.168.99.109, domain=, nis-domain=(none),
     bootserver=255.255.255.255, rootserver=255.255.255.255, rootpath=
Freeing unused kernel memory:@
init started: BusyBox v1.10.1 (2009-04-27 18:36:51 CEST)

starting pid 191, tty '': '/etc/rc.sysinit'
Thu Jan  1 00:00:00 UTC 1970
Mon Jan  1 00:00:00 UTC 2007
umount: cannot umount /initrd: Invalid argument
freeramdisk: can't open '/dev/rd0': No such file or directory
Setting up for ST7109
kb: module license 'Proprietary' taints kernel.
frontpanel: only LEDs mounted
PHY: 0:1f - Link is Up - 100/Full
input: Kreatel IR-keyboard/remote as /class/input/input0
ir_vip: enable interrupts
usbcore: registered new interface driver usbfs
usbcore: registered new interface driver hub
usbcore: registered new device driver usb
stm-ohci stm-ohci.0: STM OHCI Host Controller
stm-ohci stm-ohci.0: new USB bus registered, assigned bus number 1
stm-ohci stm-ohci.0: irq 168, io mem 0x191ffc00
usb usb1: configuration #1 chosen from 1 choice
hub 1-0:1.0: USB hub found
hub 1-0:1.0: 1 port detected
stm-ehci stm-ehci.0: STM EHCI Host Controller
stm-ehci stm-ehci.0: new USB bus registered, assigned bus number 2
stm-ehci stm-ehci.0: irq 169, io mem 0x191ffe00
stm-ehci stm-ehci.0: USB 0.0 started, EHCI 1.00, driver 10 Dec 2004
usb usb2: configuration #1 chosen from 1 choice
hub 2-0:1.0: USB hub found
hub 2-0:1.0: 1 port detected
usb 2-1: new high speed USB device using stm-ehci and address 2
usb 2-1: configuration #1 chosen from 1 choice
hub 2-1:1.0: USB hub found
hub 2-1:1.0: 3 ports detected
usbcore: registered new interface driver usbhid
/base/3pp/linux-st710x/linux-2.6.23/drivers/hid/usbhid/hid-core.c: v2.6:USB HID core driver
 KNAND cpu is 7100 ? 0
NAND device: Manufacturer ID: 0x20, Chip ID: 0x75
NAND device: Manufacturer ID: 0x20, Chip ID: 0x75 (ST Micro NAND 32MiB 3,3V 8-bit)
Scanning device for bad blocks
Bad eraseblock 258 at 0x00408000
Creating 1 MTD partitions on "NAND 32MiB 3,3V 8-bit":
0x00000000-0x02000000 : "VIP19xx NANDflash partition"
yaffs Apr 27 2009 18:23:28 Installing. 
udpfilter_kreatel initializing
ir_vip: resetting all keymaps
ir_vip: adding new keymap 32
ir_vip: adding new keymap 0
ir_vip: adding new keymap 1
ir_vip: adding new keymap 2
ir_vip: adding new keymap 5
ir_vip: adding new keymap 37
ir_vip: adding new keymap 255
ir_vip: adding new keymap 254
Load module stos_core [?]		by insmod (pid 289)
Load module stsys_ioctl [253]		by insmod (pid 291)
LXLOAD(video1) : LX loaded => Base=0x40000000 - Last=0x40124af4 - Size=1198836
LXLOAD(audio1) : LX loaded => Base=0x40300000 - Last=0x4048d418 - Size=1627160
Load module stavmem_core [?]		by insmod (pid 318)
Load module stevt_core [?]		by insmod (pid 320)
Load module stcommon_core [?]		by insmod (pid 320)
Load module stpti4_core [?]		by insmod (pid 320)
Load module stclkrv_core [?]		by insmod (pid 320)
Load module stfdma_core [252]		by insmod (pid 320)
Load module stmerge_core [?]		by insmod (pid 320)
Load module sti2c_core [?]		by insmod (pid 320)
Load module stsmart_core [251]		by insmod (pid 320)
Load module stpio_core [?]		by insmod (pid 320)
Load module stdenc_core [?]		by insmod (pid 320)
Load module stlayer_core [?]		by insmod (pid 320)
Load module stvout_core [?]		by insmod (pid 320)
Load module stvtg_core [?]		by insmod (pid 320)
Load module stvid_core [?]		by insmod (pid 320)
Load module stvmix_core [?]		by insmod (pid 320)
Load module staudlx_core [250]		by insmod (pid 320)
Load module stvbi_core [?]		by insmod (pid 320)
Load module stblit_core [?]		by insmod (pid 320)
Load module sthdmi_core [?]		by insmod (pid 320)
Load module stevt_ioctl [249]		by insmod (pid 320)
Load module stpti4_ioctl [248]		by insmod (pid 320)
Load module stclkrv_ioctl [247]		by insmod (pid 320)
Load module stfdma_ioctl [246]		by insmod (pid 320)
Load module stmerge_ioctl [245]		by insmod (pid 320)
Load module sti2c_ioctl [244]		by insmod (pid 320)
Load module stsmart_ioctl [243]		by insmod (pid 320)
Load module stpio_ioctl [242]		by insmod (pid 320)
Load module stdenc_ioctl [241]		by insmod (pid 320)
Load module stlayer_ioctl [240]		by insmod (pid 320)
Load module stvout_ioctl [239]		by insmod (pid 320)
Load module stvtg_ioctl [238]		by insmod (pid 320)
Load module stvid_ioctl [237]		by insmod (pid 320)
Load module stvmix_ioctl [236]		by insmod (pid 320)
Load module stvbi_ioctl [234]		by insmod (pid 320)
Load module stblit_ioctl [233]		by insmod (pid 320)
Load module sthdmi_ioctl [232]		by insmod (pid 320)
yaffs: dev is 32505858 name is "mtdblock2"
yaffs: passed flags ""
yaffs: Attempting MTD mount on 31.2, "mtdblock2"
yaffs: block 258 is marked bad
block 259 is bad
save-splash: No splash image availible in memory
createuserproc: Added production parameters
Cannot open /flash/.userparam
Cannot open /etc/kboxuserparamoverride.xml
createuserproc: Added serial number and mac adresses
createuserproc: Added unit specific production parameters
createuserproc: Added CA key
createuserproc: Added HDCP keys
init-frontbuttons: FrontButtons not mounted
Mon Jan  1 00:00:06 UTC 2007

starting pid 348, tty '': '/usr/sbin/dropbear'

starting pid 350, tty '': '/usr/local/widevine/bin/wvclient.sh'

starting pid 351, tty '': '/usr/bin/start_platform.sh'

starting pid 353, tty '': '/usr/bin/ntp.sh'
sntp: invalid Internet address '--no--ip'
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040996c ins=0x2982
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997c ins=0x19c2
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997e ins=0x8f05
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040996c ins=0x2982
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997c ins=0x19c2
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997e ins=0x8f05
stevt: Setting New buffer Size 8192
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040809c ins=0x6182
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040996c ins=0x2982
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997c ins=0x19c2
Fixing up unaligned userspace access in "procman" pid=351 pc=0x0040997e ins=0x8f05

process '/usr/bin/ntp.sh' (pid 353) exited. Scheduling for restart.

starting pid 383, tty '': '/usr/bin/ntp.sh'
sntp: invalid Internet address '--no--ip'

process '/usr/bin/ntp.sh' (pid 383) exited. Scheduling for restart.

starting pid 386, tty '': '/usr/bin/ntp.sh'
sntp: invalid Internet address '--no--ip'

process '/usr/bin/ntp.sh' (pid 386) exited. Scheduling for restart.

starting pid 388, tty '': '/usr/bin/ntp.sh'
sntp: invalid Internet address '--no--ip'
sti2c: retrying (2/4) i2c transfer.
sti2c: retrying (3/4) i2c transfer.
sti2c: retrying (4/4) i2c transfer.
BusAccess(): Unable to read 1 bytes, address=0x0012 !
sti2c: retrying (2/4) i2c transfer.
sti2c: retrying (3/4) i2c transfer.
sti2c: retrying (4/4) i2c transfer.
BusAccess(): Unable to read 1 bytes, address=0x0012 !

process '/usr/bin/ntp.sh' (pid 388) exited. Scheduling for restart.

starting pid 401, tty '': '/usr/bin/ntp.sh'
sntp: invalid Internet address '--no--ip'
```

# Custom kernel boot log

```
Booting...
System memory: 128 MB

Video memory: 32 MB

Using Slot 1

Unpacking Image ...Done

Linux version 2.6.17.14-sh (erik@xenalinux) (gcc version 3.4.3 (STMicroelectronics Special) [build Feb 5 2007]) #1 Thu Sep 11 14:28:31 CEST 2008
STMicroelectronics STb7100 Reference board initialisation
LMI SYS setup, fixing blue dots
LMI VID setup, fixing blue dots
STb7109 version 3.x
Built 1 zonelists
Kernel command line: console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x00070000@0x00390000(FFS),0x00390000@0x0(Raw) ramtopaddress=0xAC000000 systemmemsize=131072 videomemsize=32768 rbl=2 rbl_mode=1 dbl=1 fw=2.26
PID hash table entries: 512 (order: 9, 2048 bytes)
Using tmu for system timer
Console: colour dummy device 80x25
Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
Memory: 112056k/120832k available (1580k kernel code, 8612k reserved, 280k data, 76k init)
PVR=04061100 CVR=30480000 PRR=00009300
I-cache : n_ways=2 n_sets=256 way_incr=8192
I-cache : entry_mask=0x00001fe0 alias_mask=0x00001000 n_aliases=2
D-cache : n_ways=2 n_sets=512 way_incr=16384
D-cache : entry_mask=0x00003fe0 alias_mask=0x00003000 n_aliases=4
Mount-cache hash table entries: 512
CPU: STb710x
checking if image is initramfs... it is
Overmounted tmpfs
Freeing initrd memory: 906k freed
NET: Registered protocol family 16
Generic PHY: Registered new driver
DMA: Registering DMA API.
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 4096 (order: 2, 16384 bytes)
TCP bind hash table entries: 2048 (order: 1, 8192 bytes)
TCP: Hash tables configured (established 4096 bind 2048)
TCP reno registered
bigphysarea: Allocated 1152 pages at 0x842ed000.
JFFS2 version 2.2. (C) 2001-2003 Red Hat, Inc.
io scheduler noop registered
io scheduler anticipatory registered (default)
STPIO layer initialised
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
STMicroelectronics ASC driver initialized
ttyAS0 at MMIO 0xb8031000 (irq = 122) is a asc
DMA: Registering ST40 STB710x FDMAC handler (5 channels).
STMicroelectronics - Coprocessors st231 Init
st-coprocessor-0: No RAM reserved
st231-0 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
st-coprocessor-1: No RAM reserved
st231-1 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
ST Cryptocore Version 1.5b
RAMDISK driver initialized: 1 RAM disks of 262144K size 1024 blocksize
LAN8700: Registered new driver
STMMAC driver:
	platform registration... <6>done!
	no valid MAC address; please, set using ifconfig or nwhwconfig!
STMMAC MII Bus: probed
Registrating STMMAC reboot notifier
Generic ST boards onboard flash device: 0x00400000 (4.0MB) at 0x00000000
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
 Intel/Sharp Extended Query Table at 0x0035
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x00390000-0x00400000 : "FFS"
0x00000000-0x00390000 : "Raw"
i2c /dev entries driver
i2c_st40_pio: ST40 PIO based I2C Driver
i2c_st40_pio: allocated pin (2,0) for scl (0x841f4a24)
i2c_st40_pio: allocated pin (2,1) for sda (0x841f4a34)
i2c_st40_pio: allocated pin (4,0) for scl (0x841f4b24)
i2c_st40_pio: allocated pin (4,1) for sda (0x841f4b34)
i2c_st40_pio bus 0: SCL=PIO2[0], SDA=PIO2[1]
i2c_st40_pio bus 1: SCL=PIO4[0], SDA=PIO4[1]
fan_ctrl: Activating fan monitoring
TCP bic registered
NET: Registered protocol family 1
NET: Registered protocol family 17
Freeing unused kernel memory: 76k freed
gpio: module license 'Proprietary' taints kernel.
-----------------------------------------------------
Init started
-----------------------------------------------------
Mounting filesystems
Verifying system integrity...
System integrity is intact
Mounting the flash file system
Reading configuration parameters
Running on Motorola VIP1920-9T with Firmware version 2.26
Using Vendor Class Id Motorola_VIP1920-9T
Using Bootcast Id motorola-vip1920-9t
Using SAP Id motorola.vip1920-9t
kb driver loaded
LEDs only mounted
Initialized display. Type is 0
Front_Paneldev: registered device with major 122
front_panel driver loaded
Initializing video
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Releasing font
Deinitialize Free Type Library
Graphics device closed.
Entering video active mode
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Open graphics device (width = 720, height = 576, bitdepth = 32).
Initialize Free Type Library
Loading font: /usr/fonts/Vera.ttf
Could not open /tmp/splash.bmp
Mounting flash memory
NAND device: Manufacturer ID: 0x20, Chip ID: 0x75 (ST Micro NAND 32MiB 3,3V 8-bit)
Scanning device for bad blocks
Bad eraseblock 258 at 0x00408000
Creating 1 MTD partitions on "NAND 32MiB 3,3V 8-bit":
0x00000000-0x02000000 : "KREATEL NANDflash partition"
yaffs Sep 11 2008 14:28:35 Installing. 
yaffs: dev is 32505858 name is "mtdblock2"
yaffs: Attempting MTD mount on 31.2, "mtdblock2"
block 259 is bad
PHY: 0:1f - Link is Up - 100/Full
input: Kreatel IR-keyboard/remote as /class/input/input0
ir_kreatel: Enable interrupt
IR driver loaded
No valid splash image in local storage
Bringing up the network
Reading link status...
-> Link is up
Using DHCP
IP-Config: eth0 hardware address 00:02:9b:22:b7:20 mtu 1500 DHCP
IP-Config: eth0 guessed broadcast address 192.168.99.255
IP-Config: eth0 guessed nameserver address 192.168.99.9
IP-Config: eth0 complete (from 192.168.99.9):
 address: 192.168.99.98    broadcast: 192.168.99.255   netmask: 255.255.255.0   
 gateway: 192.168.99.9     dns0     : 192.168.99.9     dns1   : 0.0.0.0         
 nfsserver: 192.168.99.9
 nfspath: 

Download parameters:
  Splash boot order: 3
  Kernel boot order: 26145
  Bootcast address : 224.2.2.2:22222
  Sap address      : 224.2.127.254:9875

***** Loading splash image *****

Using Local Storage
LS: No valid splash image available.

Unable to successfully display a splash image. Skipping splash!

***** Loading kernel image *****

Using TFTP
TFTP: Server pool attempt 1 of 1
TFTP: Server node attempt 1 of 2
Connecting to 192.168.99.9
Sending read request for vip1920-kernel
Negotiation transfer size = 2327744
Negotiation data timeout = -1 seconds
Download completed
Verifying image...
Uncompressing image...
Unmounting nand fsave entry: isCheckpointed 0
checkpoint byte count 0
save exit: isCheckpointed 0
lash...
Unloading IR module...
Loading new kernel...
Initrd at 0xb0001000, length 1141152 byDisabling FDMA
Shuting down STMMAC TX and RX DMA
tes
Command line (355 bytes):  console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x70000@0x390000(FFS),0x390000@0x0(Raw) ip=192.168.99.98::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:22:B7:20 rbl=2 rbl_mode=1 dbl=1 bch=224.2.2.2:22222 ramtopaddress=0xac000000 systemmemsize=131072 videomemsize=32768 serverid=192.168.99.9 last_key=none videomode=PAL,RGB
Kernel loaded successfully!
Starting new kernel...
kexec information
  segment[0]: 0x84600000 - 0x84827000 (0x00227000)
  segment[1]: 0xb0001000 - 0xb0118000 (0x00117000)
  start     : 0x84601000

Entering Space Enhanced Mode (32 bit)
Running 32 bit Mode
Linux version 2.6.23.17_stm23_0123 (root@cb4194954217) (gcc version 4.3.4 20091123 (STMicroelectronics/Linux Base) ) #1 PREEMPT Tue Mar 4 15:08:57 UTC 2025
Booting machvec: STb7100 Reference board
Reserve 44672 KiB for STAVMEM (28672 KiB for graphics)
STx7109 version 3.x
Chip version 3.4
Setting version to 4.0 to match commercial branding
Adjusting DDR video memory delay for cut 3.4 CPUs, LMIPL_VID_DLL2_OFF_CMD=20
Kernel command line:  console=ttyAS0,115200 bigphysarea=2048 mtdparts=Onboard_Flash:0x70000@0x390000(FFS),0x390000@0x0(Raw) ip=192.168.99.98::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:22:B7:20 rbl=2 rbl_mode=1 dbl=1 bch=224.2.2.2:22222 ramtopaddress=0xac000000 systemmemsize=131072 videomemsize=32768 serverid=192.168.99.9 last_key=none videomode=PAL,RGB
Kernel has NOT DVR support
bpa2: partition 'bigphysarea' created at 0x40702000, size 1332 kB (0x0014d000 B)
Using tmu for system timer
Using 16.594 MHz high precision timer.
console [ttyAS0] enabled
Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
Memory: 75348k/131072k available (1749k kernel code, 347k data, 92k init)
NET: Registered protocol family 16
Generic PHY: Registered new driver
Time: SuperH clocksource has been installed.
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 4096 (order: 3, 32768 bytes)
TCP bind hash table entries: 4096 (order: 2, 16384 bytes)
TCP: Hash tables configured (established 4096 bind 4096)
TCP reno registered
Unpacking initramfs...
Overmounted tmpfs
 done
squashfs: version 3.4 (2008/08/26) Phillip Lougher
JFFS2 version 2.2. © 2001-2006 Red Hat, Inc.
io scheduler noop registered
io scheduler anticipatory registered (default)
stm_hwrandom stm_hwrandom: STM Random Number Generator ver. 0.1
Kboxdev: registered device with major 120
STMicroelectronics ASC driver initialized
stasc.0: ttyAS0 at MMIO 0x18031000 (irq = 122) is a stasc
stasc.1: ttyAS1 at MMIO 0x18032000 (irq = 121) is a stasc
loop: module loaded
SMSC LAN8187: Registered new driver
SMSC LAN8700: Registered new driver
SMSC LAN911x Internal PHY: Registered new driver
SMSC LAN8710/LAN8720: Registered new driver
	MAC 10/100
No valid MAC address yet; it will be set from the console later.
	eth0 - (dev. name: stmmaceth - id: 0, IRQ #133
	IO base addr: 0xa0110000)
STMMAC MII Bus: probed
eth0: PHY ID 0007c0c4 at 31 IRQ 2 (0:1f) active
netconsole: not configured
nwhw_config: (eth0) setting mac address: 00:02:9B:22:B7:20
VIP19xx onboard NOR flash device
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
Using word write for ST M28WXX0 FLASH
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x00390000-0x00400000 : "FFS"
first erase region 1 for slave @ 3735552
0x00000000-0x00390000 : "Raw"
first erase region 0 for slave @ 0
mice: PS/2 mouse device common for all mice
i2c /dev entries driver
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
STMicroelectronics - Coprocessors st231 Init
st-coprocessor-0: No RAM reserved
st231.0 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
st-coprocessor-1: No RAM reserved
st231.1 Coprocessor -------------------------------------------
    not configured!
---------------------------------------------------------------
stm_rng hardware driver 1.0 configured
TCP cubic registered
NET: Registered protocol family 1
NET: Registered protocol family 17
stmmac_timer: TMU2 Timer ON (freq 256Hz)
preallocating 1024(1024) skbs of size 2048
Successfully pre-allocated 1024 skbs
IP-Config: Complete: 
      device=eth0ddr=192.168.99.98ask=255.255.255.0w=192.168.99.9,
     host=192.168.99.98, domain=, nis-domain=(none),
     bootserver=255.255.255.255ootserver=255.255.255.255ootpath=Freeing unused kernel memor�
init started: BusyBox v1.13.3 ()

starting pid 210, tty '': '/etc/rc.sysinit'
insmod: cannot insert 'usbcore': unknown symbol in module, or unknown parameter
insmod: cannot insert 'ohci-hcd': unknown symbol in module, or unknown parameter
insmod: cannot insert 'ehci-hcd': unknown symbol in module, or unknown parameter
insmod: cannot insert 'usbhid': unknown symbol in module, or unknown parameter

starting pid 221, tty '': '/usr/sbin/telnetd'

starting pid 223, tty '': '/bin/sh'


BusyBox v1.13.3 () built-in shell (ash)
Enter 'help' for a list of built-in commands.

/bin/sh: can't access tty; job control turned off
/ # PHY: 0:1f - Link is Up100/Full
/ # id
uid=0 gid=0
/ # ls -l
drwxrwxr-x    2 0        0            1060 Jan  1 00:00 bin
drwxr-xr-x    4 0        0            2180 Jan  1 00:00 dev
drwxrwxr-x    2 0        0             100 Jan  1 00:00 etc
lrwxrwxrwx    1 0        0              10 Jan  1 00:00 init -> /sbin/init
drwxrwxr-x    2 0        0             160 Jan  1 00:00 lib
dr-xr-xr-x   28 0        0               0 Jan  1 00:00 proc
drwxrwxr-x    2 0        0             440 Jan  1 00:00 sbin
drwxr-xr-x   10 0        0               0 Jan  1 00:00 sys
drwxrwxrwt    2 0        0              40 Jan  1 00:00 tmp
drwxrwxr-x    4 0        0              80 Jan  1 00:00 usr
/ # cat /pro
/ # cat /proc/[Jver[9D
/ # cat /proc/version [J
Linux version 2.6.23.17_stm23_0123 (root@cb4194954217) (gcc version 4.3.4 20091123 (STMicroelectronics/Linux Base) ) #1 PREEMPT Tue Mar 4 15:08:57 UTC 2025
/ # busy
/ # busybox [Jversion
version: applet not found
/ # 
/ # busybox version[J       -v
-v: applet not found
/ # 
/ # busybox -v[J   
BusyBox v1.13.3 () multi-call binary
Copyright (C) 1998-2008 Erik Andersen, Rob Landley, Denys Vlasenko
and others. Licensed under GPLv2.
See source distribution for full notice.

Usage: busybox [function] [arguments]...
   or: function [arguments]...

	BusyBox is a multi-call binary that combines many common Unix
	utilities into a single executable.  Most people will create a
	link to busybox for each function they wish to use and BusyBox
	will act like whatever it was invoked as!

Currently defined functions:
	[, [[, ash, awk, basename, brctl, bunzip2, bzcat, cat, chgrp,
	chmod, chown, chroot, clear, cp, cut, date, dd, df, dirname, dmesg,
	du, echo, egrep, env, expr, false, fdisk, fgrep, find, freeramdisk,
	ftpget, ftpput, grep, gunzip, gzip, halt, head, hostname, id,
	ifconfig, init, insmod, ip, ipaddr, iplink, iproute, kill, killall,
	ln, losetup, ls, lsmod, md5sum, mdev, mkdir, mkfifo, mknod, mkswap,
	mktemp, modprobe, more, mount, mv, netstat, nslookup, pidof, ping,
	poweroff, printf, ps, pwd, reboot, renice, reset, rm, rmdir, rmmod,
	route, sed, sh, sleep, sort, strings, swapoff, swapon, sync, tail,
	tar, telnet, telnetd, test, tftp, time, top, touch, tr, traceroute,
	true, udhcpc, umount, uniq, uptime, usleep, vi, watchdog, wc,
	wget, which, xargs, yes, zcat, zcip

/ # 
```
