# After Hours at Bellweather

**A campus mystery developed by Dr. Malik Stalbert.**

## Download the Windows game

Download the corrected Windows v0.2.1 game:

- **[Complete EXE download](https://github.com/awayzo/after-hours-at-bellweather/releases/download/v0.2.1/Bellweather-Windows-v0.2.1.exe)** — run it, let it prepare the game files, and choose Play game. The complete game is embedded; no additional download is needed.
- **[ZIP alternative](https://github.com/awayzo/after-hours-at-bellweather/releases/download/v0.2.1/Bellweather-Windows-v0.2.1.zip)** — extract the entire ZIP, open its folder, and double-click Bellweather.exe.
- **[Release notes and checksums](https://github.com/awayzo/after-hours-at-bellweather/releases/tag/v0.2.1)**

SMILE GAME BUILDER, Steam, Visual Studio, an SDK, csc.exe, and .NET Framework 3.5 are not required. The game uses Windows' built-in .NET Framework 4.x runtime. This is a Windows desktop release; a browser version is not included. GitHub's Source code downloads are not the game.

**OpenGL startup error:** use Play with software graphics in the complete EXE launcher, or Bellweather Software Graphics.exe in the ZIP folder. The included Mesa renderer installs no driver and changes no system graphics settings. It uses the CPU and may run more slowly, particularly in virtual machines.

The complete EXE stores its game files in %LOCALAPPDATA%\Bellweather\Windows-v0.2.1. Keep the EXE to launch again. ZIP users keep all extracted files together in a writable folder. When updating, back up your old folder and copy only savedata into the new game folder; do not copy old scripts or DLLs over this repair.

## The story

Your CIT 140 field project sounded simple: investigate missing room bookings and recommend a fix. Then a printer issues a reservation in your name for Room 214—a room in a building that closed six years ago. The meeting starts at 2:13 a.m.

Your partner Jules wants to clear a family name. Mina knows which records survived the closure. Theo can tell you what the locked doors actually prove. Malik appears when an investigation goes wrong, and seems to know which question you were about to ask.

Follow the trail across Bellweather College, investigate the lights in Lantern Woods, and decide whom to trust when your work leads beyond campus. Your character recognizes places she believes she has never visited.

## Playing

- **Arrow keys:** move and navigate choices.
- **Enter or Z:** inspect, talk, advance text, and confirm.
- **Escape or X:** cancel or open the game menu when available.
- Walk onto doorways to move between locations.
- Face people, bookshelves, desks, notices, and equipment and press Enter to investigate. Every clue does not have a floating icon.
- Use blue-bound casebooks to save, review evidence and remembered conversations, read phone messages, and check course progress.

The **START HERE.txt** file included with the download has the full player guide.

## Food, charging, and rest

Visit **Lantern House**, southwest of the Quad. Follow the southward blue arrow beside the gatehouse and use the night desk for rest, meals, water, and phone charging. Reading and conversations pause the travel clock. This verified version includes the earlier forgiving needs system.

## Course progress

You can earn up to **50 course points** through investigation and analysis. Open **Casebook → Course score / credit** to see category totals and your BW1 progress code. Choose **Copy code and save a receipt** to export a receipt to **Documents / Bellweather Receipts**.

Keep the full progress code and your saved game. Post found items, screenshots, and your explanation in **your course Discord**. Your instructor will provide Canvas submission instructions.

The Canvas portal is planned separately. The current code is an unsigned progress receipt for instructor review; this game does not post grades automatically.

## Version and testing

**v0.2.1 repairs the v0.2.0 startup dependency and title mouse selection.** Scripts are compiled during packaging, so the game no longer looks for a C# compiler on the player's computer. Options opens settings and Begin investigation starts the story; quick background clicks and disabled Continue no longer confirm the default action.

Native checks covered 30/50 and 50/50 course points, receipt export, and save/load. The shipped scoring DLL passed valid-state receipt round-trips and score-cap checks; the existing instructor reviewer remains compatible. The complete EXE extracted its payload and launched the game. Bundled software graphics reached the 3D opening scene on this Windows host.

These checks ran on the development Windows computer. A second clean Windows machine and the reporter's virtual machine have not yet been tested with the repair. The release remains a pilot prerelease. Please report the game version, Windows version, graphics mode, last action, and an error screenshot. Full verification details are attached to the release.

The next update is still in testing. Its rival inn, survival consequences, new repair task, detailed earned-point ledger, textured HUD, and animated per-award receipts are **not included in v0.2.1**. That update will receive its own release after verification.

## Credits and rights

Developed by **Dr. Malik Stalbert**, using SMILE GAME BUILDER. Engine and third-party asset rights remain with their respective owners. The download is a playable game; it does not grant permission to extract or reuse its engine, music, artwork, or models in other projects.

Do not post personal save files or receipt codes publicly when reporting bugs.

