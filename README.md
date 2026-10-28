FDS Emulator
A program that lets you play Famicom Disk System games on your computer.

Website: https://b84308463-blip.github.io/FDS-EMULATOR

GitHub: https://github.com/b84308463-blip/FDS-EMULATOR

What it does
Plays games the right way, very close to the real thing

Shows the game on your screen

Plays the game sounds and music

Reads game files and lets you change disks

Lets you save your game at any time and go back if you make a mistake

Works with your keyboard or a game pad

How to play on the website
Go to your website link and play right in your web browser. No need to download anything!

How to build it for your computer
bash
git clone https://github.com/yourname/fds-emulator.git
cd fds-emulator
mkdir build && cd build
cmake ..
cmake --build . --config Release
You need CMake and SDL2 to build it.

How to run it
bash
./fds-emulator --bios /path/to/disksys.rom /path/to/game.fds
You must use your own FDS BIOS file (disksys.rom).

Buttons
What you want to do	Key to press
Move	Arrow keys
Jump / Fire	Z / X
Start / Select	Enter / Right Shift
Change Disk	F2
Save / Load Game	F5 / F8
Go Back in Time (hold)	Backspace
Full Screen	F11
Pause	P
Restart	Ctrl+R
Settings
You can change settings in a file called config.ini:


ini
[video]
scale = 3
vsync = true


[audio]
sample_rate = 48000


[fds]
bios_path = bios/disksys.rom
fast_disk = false
write_protect = true

Rules

This program is only for learning and keeping old games alive. It does not come with any game files or BIOS files. Famicom and Famicom Disk System are owned by Nintendo. This project is not made by Nintendo.
