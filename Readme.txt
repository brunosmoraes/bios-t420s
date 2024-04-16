Lenovo T420s v1.46 Modified Bios

- Whitelist removal
- Unlocked AES-NI on "no-encryption" machines
- Unlocked hidden advanced menu
- Unlocked memory speed (supports DDR3 1600 and 1866)
- Disabled package c-state lock at MSR 0xE2 (for Hackintosh)
- Re-signed with custom key to get rid of 5 beeps on boot


Flash original BIOS image first, then use flash.bat to flash BIOS
If you on 1.46 already, use "flash.bat" to flash BIOS. No need to flash original BIOS image prior to flashing modified one.

Be careful with advanced menu. Changing some options may render your laptop unbootable!
More memory speed means more heat, 1866 MHz memory speed may increase your laptop temperature up to 5°C.


---------------

mtwei