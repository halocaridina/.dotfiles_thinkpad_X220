
SheepShaver 2009-10-25 ReadMe

This build was compiled from source as it existed in CVS on 25 October 2009 (with the exception of the 19 February 2009 sdl-audio patch and the 17 August 2009 precise timer patch).

This build should work in MacOSX 10.4 (Tiger) and 10.5 (Leopard) on PPC and Intel Macs and it will probably work in 10.6 (Snow Leopard).

If you have an existing SheepShaver setup, you can simply replace the application with the new application.

If you set up SheepShaver for the first time, you will also need a compatible ROM file and a retail MacOS install CD (or a install CD disk image). For other than US English keyboard layouts the included keycodes file is needed.

See the setup manual for more information.

Questions and comments please on Emaculation SheepShaver forum:
http://www.emaculation.com/forum/

Improvements in 25 October 2009 build:
- Fix for freeze or crash at startup on some host machines that was introduced in the previous build.

Improvements in 18 October 2009 build:
- "Cannot map RAM" error on Leopard fixed
- The emulated machine can now use more than 512 MB of RAM
- When a rom file is not set in preferences, a rom file in the current directory with default name "Mac OS ROM" or "ROM" will now always be found (not only on first boot)
- A crash that could occur while booting a new virtual/emulated machine (creating a new nvram file) with MacOS 7.5 fixed
- Support for self-contained virtual machine bundles with extension .sheepvm
- Removed audio patch (still in cvs) that caused degradation of sound performance rather than the intended improvement
- Problems with copy and paste of styled text in some applications fixed

Improvements in 19 March 2009 (full-screen) build:
- Full-screen support
- Possible improvement of sound performance on slow host machines

Improvements in 21 July 2008 build:
- Mouse buttons correctly numbered
- If no ROM can be opened, SheepShaver will quietly quit instead of hang
- Refresh Rate "Dynamic" sets correctly frameskip to "0" and is now the preferred setting on fast host machines

Some of the earlier improvements since the latest 'official' release version (2.3-Pre, 14 May 2006):
- Greatly improved performance on Intel machines (JIT compiler)
- Correct handling of resource forks and TYPE/CREATOR codes of files transferred through the shared folder (Unix Root)
- Corrected cursor placement and display of colored cursors
- Built-in Preferences editor


Disclaimer:
I am not a software developer, just a user, a hobbyist like you probably are. I built the application from the source code, written by others, as it is available in CVS. I can give no guarantee that this software will work or that this software will not damage your files or your system. If you use this software, all possible consequences are your own responsibility.


25 October 2009
Ronald P. Regensburg
Amsterdam, Netherlands