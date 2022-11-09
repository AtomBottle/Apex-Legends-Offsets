# Apex-Legnds-Offsets
By https://github.com/CasualX/apexbot

## About 
#### Last update time `2022-11-9` & Game Version `v3.0.18.33`
i usually update on weekends so i wrote a simple guide about it

## Guide
### First of all
install Rust `https://www.rust-lang.org/tools/install` <p>
Then clone or download  https://github.com/CasualX/apexbot
  
### Compile
For Example i use VisualStudio<p>
1.Creat a new project.Then,put src/stdafx.cpp into it<p>
2.After that,add src/ to inclued directories<p>
3.complie
### Dump apex legends from memory  
Follow https://github.com/CasualX/apexbot to bypass EasyAntiCheat&Start the game<p>
Wait a second,r5apex.bin will be in /your project/r5apex.bin
### In the End
Copy r5apex.bin to /apexbot-master/offsets<p>
From there you can dump its offsets with `cargo run --release -- "r5apex.bin" ini > stdout.ini`. <p>
The script will analyze the dumped binary and extract its offsets. Use these offsets to update the cheat. <p>
You can get human readable output without offsets with `cargo run --release -- "r5apex.exe" human > stdout.md`.
## Raw
[CDN](https://cdn.githubraw.com/AtomBottle/Apex-Legends-Offsets/main/stdout.ini)
<h1>Enjoy!
  
