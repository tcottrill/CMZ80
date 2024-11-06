* Zilog Z80 processor emulator in C. Modified to be API compliant with Neil
 * Bradley's MZ80 (for ported projects)
 * Ported to 'C' by Jeff Mitchell; original copyright follows:
 *
 * Abstract:
 *   Internal declarations for Zilog Z80 emulator.
 *
 * Revisions:
 *   18-Apr-97 EAM Created
 *   ??-???-97 EAM Released in MageX 0.5
 *   26-Jul-97 EAM Fixed Time Pilot slowdown bug and
 *      Gyruss hiscore bugs (opcode 0xC3)
 * Original copyright (C) 1997 Edward Massey <br/>

This is an "upgrade" of an original CMZ80 Emulator used in Generator and Retrocade, circa 1997. <br/>
I have found that even though there are many Z80 emulators out there, there is a big difference between "passes zexdoc perfectly" and "really works to emulate a video game such as Galaga" <br/>

This has been converted to a C++ class, and has many updates to work with at least a little bit more modern programming. Several bugs have been fixed, as well as many code updates. <br/>
See Z80.h for all updates.<br/>
Now passes Zexdoc with no issues! <br/>
An example has been included of a working Space Invaders emulator to get someone started if they would want to experiment with it.<br/>

This code has been tested to work properly with:<br/>
Pacman, Bosconian, Galaga, Space Invaders, Omega Race, Rally X and Sega vector games.<br/>
All code remains copyright the original authors.<br/>
