Cleanup of the SuperQOT Darkplaces fork that's focused on ease of use.
Any support for ancient VC versions/non VC compilation/non-x64 has been dropped.
All deps (really only SDL) are included.

To use: Get the source, get Visual Studio 2022, open the Solution, compile, done.

To play:
Get the latest release from the Releases page, add PAK0.PAK and PAK1.PAK from any Quake1 release to the id1 folder and launch SuperQot.exe
Game is pre-configured for WASD

Additional controls:
Mouse 2: Sniper
Mouse 3: Real-time

Rules for slow-mo are as follows:

Player speed equals speed of game
On ground time can't go below 0.01x real-time
While in the air or in water time can't go below 0.1x real-time (so you don't get stuck in the arc of a jump)
While the shooting button is pressed time can't go below 0.25x real-time (so that the bullets actually move)

Have fun :)
