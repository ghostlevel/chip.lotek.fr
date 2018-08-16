# chip.lotek.fr — NTC's CHIP mirrors & resources

<pre>
._______ .___.__  .___ ._______ 
:_.  ___\:   |  \ : __|: ____  |
|  : |/\ |   :   || : ||    :  |
|    /  \|   .   ||   ||   |___|
|. _____/|___|   ||   ||___|    
 :/          |___||___|         
 :                              
</pre>

(latest modification: 2018-08-16)
***

## archives/backups/mirrors

- [mirror of NTC's CHIP .deb repositories](http://chip.lotek.fr/chip/) (Debian Jessie)

for your "/etc/apt/sources.list", you can use

<pre>
deb http://chip.lotek.fr/chip/debian/repo jessie main
deb http://chip.lotek.fr/chip/debian/pocketchip jessie main
</pre>

>(The 2nd repository -2nd line- contains PocketCHIP's specific packages.)


You should also replace the nextthing.co url in "/etc/apt/preferences" & change it to
<pre>
Package: *
Pin: origin chip.lotek.fr
Pin-Priority: 1050
</pre>

> If Pico-8/another software crashes with SDL errors after you used this repo, modify '/etc/apt/preferences' as above & *sudo apt upgrade* should fix it.

>(Thanks [jfp](http://chip.jfpossibilities.com/))

- [Online NTC/CHIP documentation](/docs.getchip.com/)

- [cli-images](/cli-images/) 

- [chp-images](/chp-images/) - partial
- [CHIP Flasher Chrome extension](/misc-files/CHIP%20Flasher%205.0.0_0.zip)

> 2018-08-06: The online flasher doesn't work anymore, follow CLI/terminal guides do flash from a Linux machine.



***

### CHIP links

  
 — [JF Possibilities' NTC mirror](http://chip.jfpossibilities.com/)
 / (See [forum](https://bbs.nextthing.co/t/planning-for-the-inevitable/19958), [warc](misc-files/bbs-ntc-planning-for-the-inevitable-thread.warc.gz))
 >Bookmark the above link in case chip.lotek.fr goes down. And bookmark the community wiki, and— *more importantly: don't forget all the archive.org stuff, they will, or should, stay up longer than the rest of us.*

 — **[chip community wiki](http://www.chip-community.org/index.php/Main_Page)**

 — *[C.H.I.P. Flash Collection @ archive.org](https://archive.org/details/C.h.i.p.FlashCollection) & [more](https://archive.org/search.php?query=creator%3A%22Next+Thing%2C+Co.%22)*

 — *[NTC Git Archive](https://archive.org/details/NextThingCo.GitArchive)*

 — [How to Flash C.H.I.P Offline](https://yoursunny.com/t/2018/CHIP-flash-offline/) / ([simple stupid .html copy](yoursunny.com-how-to-flash-CHIP-offline.html))

 — [Reflashing The PocketCHIP Without The Online Flasher (On Linux) - pdf](/misc-files/Reflashing%20The%20PocketCHIP%20Without%20The%20Online%20Flasher%20On%20Linux.pdf) / ([og thread](https://bbs.nextthing.co/t/reflashing-the-pocketchip-without-the-online-flasher-on-linux/20614/4))

 — [CHIP_IO](https://github.com/xtacocorex/CHIP_IO), A CHIP IO library for Python: IO+PWM+SPWM+ADC+Utilities

 — [NTC's documentation on the Wayback Machine](https://web.archive.org/web/20161119024310/http://docs.getchip.com:80/) // or download the [archive file](/misc-files/docs.getchip.com.tar.bz2)



> — [linux-sunxi wiki for Allwinner SoCs](https://linux-sunxi.org/Main_Page)
>
> — [awesome-chip](https://github.com/Project-chip-crumbs/awesome-chip) GH page
>
> — [kaplan2539 unofficial's kernel & repo](https://github.com/kaplan2539/CHIP-Debian-Kernel) - ([forum thread](https://bbs.nextthing.co/t/new-kernel-4-4-138/20894)) // [personal mirror repo](/kaplan2539-CHIP-Debian-Kernel/) (2018-07-28) // Probably not tested on a pCHIP?
>
> & [How to compile just one kernel module](https://yoursunny.com/t/2018/one-kernel-module/) / ([simple stupid .html copy](yoursunny.com-one-kernel-module.html))
>
> — [v10lator's kernel repo](https://chiprepo.home.v10lator.de/) - ([forum thread](https://bbs.nextthing.co/t/release-alternative-community-driven-kernel/18818)) // [info txt](v10lator-kernel.txt) / [personal mirror repo](/v10lator-kernel/) (2018-07-28) // ([WARC](misc-files/bbs-ntc-release-alternative-community-driven-kernel-18818.warc.gz)) // i think it hasn't been tested on a pCHIP & *won't work on a pCHIP*
>
> — [a personal HOWTO to compile the Linux kernel for Chip](http://www.raspibo.org/wiki/index.php/Compile_the_Linux_kernel_for_Chip:_my_personal_HOWTO) - ([WBM](https://web.archive.org/web/20180731160444/http://www.raspibo.org/wiki/index.php/Compile_the_Linux_kernel_for_Chip:_my_personal_HOWTO)) & [on the CHIP itself](http://www.raspibo.org/wiki/index.php/HOW-TO_compile_Chip%27s_Linux_kernel_and_modules_on_Chip_itself)
>
> — [utilities for exploring .chp files](https://gitlab.com/wh0/chip-setup) 
> 

### community links

> — [NTC unofficial Discord](https://discordapp.com/invite/M2wa9RV) / [TheBoardRoom](https://discord.gg/b8jd2wZ)
>
> — #chipsters on Freenode
>
> — [chip-crumbs ggl group](https://groups.google.com/forum/#!forum/chip-crumbs)
>
> — [Chipsters' slack](https://slofile.com/slack/chipster)


### misc 
 — [Phase](http://www.humbletune.com/phase/),  "Phase is a phase distortion synthesizer written for the pocket chip." (Also runs on Raspberry Pi)

 — [extend life of the NAND/flash](http://www.chip-community.org/index.php/Flash#Extend_life), ramdisks, etc. 

 — [turning CHIP into a BT Audio Receiver (Audio Sink) & Guide to connecting to a Bluetooth Speaker](http://chip.lotek.fr/misc-files/CHIP-into-BT-Audio-Receiver+connecting-to-BT-speaker.md) txt/md copy 

 — [ElKentaro's HackCHIP V1. (part 1/n)](https://medium.com/@elkentaro/hackerchip-v-1-part-1-of-n-59804d27c245)

 — CHIPMAS [github](https://github.com/nyboer/CHIPMAS), [hackter.io](https://chip.hackster.io/11802/c-h-i-p-midi-arpeggiating-synth-e311ab), CHIP MIDI Arpeggiating Synthesizer is a simple Pure Data synthesizer. Wavetable synth, control by OSC/MIDI. 


 — [wlan_pwr](https://github.com/fordsfords/wlan_pwr), improve CHIP wireless perf and reliability by turning off power mgt 

 — [PocketDESK](https://github.com/AllGray/PocketDesk), unify Desktop GUI & PocketHome
 
 — [PocketCHIP Launcher](https://github.com/o-marshmallow/PocketCHIP-pocket-home) (Marshmallow Edition)
 
 — [pocket-home freedesktop launcher](https://github.com/centuryglass/PocketCHIP-pocket-home), application launcher that follows the freedesktop standard


 — [pocketInstaller](https://github.com/IkerGarcia/PocketInstaller), a GUI to install emulators/games

— [Running Processing on NTC's CHIP](https://github.com/processing/processing/wiki/C.H.I.P.) + [Processing 3+ sketches optimized for the PocketCHIP](https://github.com/Lana-chan/chip-processing)


