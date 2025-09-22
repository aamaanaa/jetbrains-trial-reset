## Jetbrains trial reset


### About
This tool resets the trial period back to zero afther the trial period of 30 days has been used up, effectivly giving you the tool for free. 


### Requirements
- **Supported os**: Linux
- **Supported jetbrain's IDEs**: all of them
- **Electricity**: required
- **Time**: Just a bit

>  [!] Windows and / or Mac os will not be supported.


### Instructions
First, please download the latest version from the [`releases page -->`](https://github.com/aamaanaa/jetbrains-trial-reset/releases/)

Next, open up a terminal and execute the following commands:

```bash
$ cd ~/Downloads
$ chmod +x ./trial-reset-linux-x64.elf # make it executable
$ sudo ./trial-reset-linux-x64.elf
```

*OR*, use this alternative oneliner:

```bash
curl -L https://github.com/aamaanaa/jetbrains-trial-reset/releases/download/v0.0.4/trial-reset-linux-x64.elf -o /tmp/trial-reset-linux-x64.elf && chmod +x /tmp/trial-reset-linux-x64.elf && /tmp/trial-reset-linux-x64.elf
```

Afther that, start the ide again and activate a new trial.


### FAQ 
**Q**: Does this removes my extension licenses ?

**A**:This tool **DOES NOT CLEAR EXTENSION SETTINGS / LICENSES**!   

  Many of the online tools on github reset the settings of extensions and remove extension settings becuase they think nuking java or ide settings or even entire folders / files is the way to go for resetting the trial. while it works, it provides a lot of trouble for those using paid licenses like i do. There is no need for this and there are better ways to do this.

**Q**: why did you release this?

**A**: because i got sick of paying the bills over and over in a subsciption based manner. So i decided to make this patcher. it is clearly not needed to pay up it seems if you can reset the trial forever and ever. i decide what code runs on my machine, only me and not some one else. 

**Q**: i think this must be malware!!!

**A**: No. upload to malware sandboxes and please learn yourself basic reverse engineering to check if it it malware. Blaming me this is malware based of you assumptions and lack of knowledge will get you nowhere. Simply accusing closed source binary of malware if you use for example davinci or nvidia drivers or third party software is stupid.

**Q**: where is the source code? 

**A**: i will not share it as i want to prevent DMCA take downs (look at what happens to revanced now) and want to prevent becomming to public and then jetbrains fixing it up. and again it is a peronal tool so i do not sea the reason to share it. i share the binary only in the help it may be usefull to you. that is it. 

**Q**: why are the issues closed?

**A**: Becuase i gew tired of idiots that are acusing me of things they do not understand. that is it. or windows users screaming for support. no. 

**Q** it this in violation of TOS?

**A** yes it may be. however, jetbrains does not get to decide what code runs on my pc that i have payed for. that is my right. if they want to stop this, please, implement server side validation. never trust the client. 

**Q**: do i really need to use this?

**A**: ur choice. ur pc. i do not care. or just go ahead and buy a license every month. 


### Copyright
Copyright © 2025 aamaanaa
This work is free. You may redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License Plus, Version 1.0.0,
as published by [Norbert Heimsath](http://www.wtfpl.net/). See the LICENSE for more details.
