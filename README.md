### Description
This is a trial reset tool that can reset the trial period of any JetBrains IDE. It aims to only reset the trial period,
and to not delete any of your settings, or license keys that you may have, unlike other tools that are available.

### Requirements
- Supported os: Linux (for now)
- Supported IDEs:
  - JetBrains IDEs (e.g., PyCharm, IntelliJ IDEA, etc.)

### Usage
- Download the binary from the Releases page.
- Open up a terminal, cd into the directory where you downloaded the binary.
  ```bash
    cd ~/Downloads
  ```
- Make it executable:
  ```bash
  chmod +x trial-reset-linux-x64.elf
  ```
- Exit any JetBrains IDEs that are running.
- Run the binary:
  ```bash
    ./trial-reset-linux-x64.elf
    ```
- Accept the prompt that appears.
- That is it!

### FAQ
- **Q: How does it work?**
  - A: I will not disclose this. JetBrains is known to scan for GitHub repositories that contain this information,
    and then submitting a DMCA request to take it down. If you really want to know, you have to reverse engineer it.
    - See also: [JetBrains DMCA takedown](https://github.com/github/dmca/blob/master/2022/04/2022-04-13-jetbrains.md)

- **Q: Is it safe to use?**
  - A: Yes, the software does not need root and does not need the internet. However, be reminded that this may change due to  
    the way JetBrains implements their trial system in the future.

- **Q: Is the operating system x supported?**
  - A: Currently, only Linux is supported. However, I plan to add Windows and macOS support in the future.

- ****     



### DISCLAIMER:

This software is provided as-is, and the creator assumes no responsibility for how it is used.
Any actions taken with this software are the sole responsibility of the user.
The creator disclaims all liability for any misuse, damages, or legal consequences that may result from its use.

By choosing to use this software, you accept full accountability for your actions and acknowledge that the creator
cannot be held responsible for any accusations, issues, or outcomes arising from its use.

Use this software at your own risk.
