BoS
=========
Ace of Spades classic client fully compatible to the old voxlap client and openspades.
It is able to connect flawlessy to 0.75 servers. BoS also provides the ability to modding using KV6-files.
The client is in early beta, so there are still plenty of things left to finish and bugs to fix.

The whole concept of this is to not just provide another client to the already existing ones; OpenSpades and Voxlap;
but actually give a solution to the problem of the whole community. It shall fix the moving (not) forward problem we face
and supersede especially the old voxlap client on older computers. It is still fast enough to run on your grandmother's rig,
while also new enough to reach new players for the AoS-community that want fancy graphics and an enhanced gameplay experience.

First start
=========

The project's concept in mind the client is designed to just replace the original client.exe in the Ace of Spades directoy, so
it would be easy for users to update to the new client. 


Installing should be very easy then:

Just grab a release from my website over at http://bytebit.info.tm/builds/battleofspades/ or feel free to build the
client yourself. Just make sure to always download the newest release. Extract the 'client.exe' out of the zipped file
and replace the existing one. There are only three other new files in the png directoy that you should also copy-paste to your
local png-folder. These are 'loading.png', 'vignette.png' and 'noise.bmp', where last one is an optional texture for blocks.

Compiling
=========
Requires full PureBasic 5.31 or a similar version. This project won't compile with the demo version,
because it is over the line limit (around 6700 lines of code).

Also needed is the High precision timer library for PureBasic which you can find here:

http://www.purebasic.fr/english/viewtopic.php?f=14&t=49325

(better use the x86 version and put it in your UserLibrary folder)

Also newest versions now require OpenAL, BoS therefore uses SoftAOL. Just rename it to 'soft_oal.dll' and place it in the
root directory.

Gameplay
=========

WASD	- basic movement

Mouse	- change camera rotation

0+1		- join Blue team

0+2		- join Green team

0+3		- join Spectator team

1234	- switch weapons

M Wheel - switch weapons

Escape  - enter/exit pause menu

LMB		- primary attack

RMB		- secoundary attack (depends on equipped item)

L		- show light view (only in shadow mode)

R		- reload weapon


Helping out
=========
If you like you can help me by sending me your benchmarks of the client (use Fraps or something else).

Please also provide information about your graphics card and cpu.

Head over to http://bytebit.info.tm/benchmark.php to submit your data.