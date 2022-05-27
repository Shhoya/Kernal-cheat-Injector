# Kernel cheat injector
Inject your internal dlls with this please read before using for your safety as this is public and I am not responsible for any bans you may face.

# updated 18/05/2022
- changed driver issues 
  - fixed bsod issues when anticheat loads 
  - fixed hosting server not streaming bytes
  - bypass guarded regions
  - dll size can now be higher than 1mb 


# changes
 - 20/04/2022
   - WindowsHook -> added ( how to use ? | enter your dll filepath + the name of the dll | then simply write what you want the output name to be ( example "cheat" )
     what does it do ? | it converts your dll into bytes allowing the injector to read the dll bytes and inject them into your targeted game.
   
# if you want to purchase the Full Source add my discord skeng#9524


# active updates + changes to keep this undetected and safe to use !
## - Make Sure you read how to use and the rest of the information about this.  
be kind and leave a star

<img src="https://i.ibb.co/Cngyv9n/Capture.png">



# lost ark
<img src=https://media.discordapp.net/attachments/947722414551351326/949319472324423740/unknown.png>


# how to use ?
- run v2 injector ( wait around 15-20 seconds if black screen shows this is due to the software trying to find vulnrable modules to inject to on your pc )
- make sure your dll is in the same folder as injector
- run injector before opening game ( if you face vuln error disable antivirus and firewall )
- rename your dll to rwx1.dll
- launch your game ( must be on the same drive as injector )
- input the window class name of the process you are wanting to inject into 
- rwx will exploit the games imports and then proceed  to inject into the games window hook
- 

# some window class names examples
UnrealWindow - Fortnite, Valorant , Splitgate 
UnityWndClass - Rust, Escape From Tarkov
Respawn001 - Apex legends


# how status works 🔵 = undetected | 🔴 = detected
## working anti-cheats that injector supports
* Vanguard 🔵
* Easy Anti Cheat🔵
* BattlEye Anti Cheat🔵
* FACEIT 🔵
* Valve Anti-Cheat🔵
* PunkBuster🔵
* NProtect GameGuard🔵
* Ricoche🔵


# windows versions from 1909 / 20h2

# little insight on the release
i thought not many people release working injectors these days that can actually inject past EAC and other anti-cheats i want to be able to provide a working injector for upcoming cheat developers or just individual people who dont understand code and want to cheat on a anti-cheat protected game.

## why not release injector source and driver source?
because i dont agree with the fact of many people skidding on developers work in this category ( fair enough for cheats ) but injectors and drivers are more important to keep private although i will sell this source code for a reasonable price.


# extra features ( with the source code )
- the source code is not public version it will be a completely undetected injector + driver along with a custom mapper allowing you to bypass vangaurd + faceit blocking methods
- rwx injection methods 
- dump game offsets + signatures ( Engines supported Ue4, Ue5 , Unity )
- UI Mode ( imgui mode of the injector )
- dump games + the game pdb ( some games dont work )
- you can use detours + minhook
- decrypt warzone offsets
- dump offsets for all titles + auto sig maker
- choose what injection format you want x86 / x64
- IAT dumper
- Anti-Cheat Emulator ( allowing you to do anything you want practically )

## how to find my games window class ?
- if you have visual studio downloaded make sure you have c++ installed
- open any blank project in visual studio
- head over to tools tab and look for spy++
- once spy++ is open use the find window tool in the app
- simply drag the spytool over your game window ( it has to be in windowed mode to find the window class )


## find window class method 2
- head over to https://www.nirsoft.net/utils/winlister.html and download winlister x64 or x32
- open it up look for your process for my example i will use notepad
- right click on the process that you are wanting to inject into 
<img src="https://i.ibb.co/BL79h5h/tempsnip.png">

# To buy the source for rwx injector source code contact me via discord: skeng#9524
or if you are wanting to purchase other sources or want something developed let me know


# added test.dll for testing if injector works :)
