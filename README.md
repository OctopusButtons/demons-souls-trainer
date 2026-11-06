# Credit & Original Source

Forked from https://github.com/13xforever/demons-souls-trainer

See [below](#The-purpose-of-this-fork) for the purpose of this fork.

# How to Use

Instructions from user georg-zeiser who [helpfully answered my public question](https://github.com/OctopusButtons/demons-souls-trainer/discussions/1) for how to use this:

1. Download the zip file from the original project. Get the version from 02.07.2024, based on .net 8, this how-to might not work with other versions.
2. Extract the zip file, there is a `.dll` file and an `.exe` file
3. Copy the attached file `DesTrainer.runtimeconfig.json` into same folder
[DesTrainer.runtimeconfig.json](https://github.com/user-attachments/files/33878922/DesTrainer.runtimeconfig.json). For transparency, the entire code of the `.json` file is (as you can see if you open the `.json` in a text editor):
```
{
  "runtimeOptions": {
    "tfm": "net8.0",
    "framework": {
      "name": "Microsoft.NETCore.App",
      "version": "8.0.0"
    }
  }
}
```
4. Now you should have 3 files:
   - `DesTrainer.dll`
   - `DesTrainer.exe`
   - `DesTrainer.runtimeconfig.json`
4. Make sure, you have **.net 8** installed
5. Execute `DesTrainer.exe`.  You should see a console window with text "Searching for the process...".
6. Start RPCS3
7. Start the EU version of the game (BLES00932)

The text "Searching for the process..." disappears. As soon as you are in the game and have health-/staminabar, the values will never decrease and the values are also shown in the console window.

# The purpose of this fork
I forked this trainer repository from https://github.com/13xforever/demons-souls-trainer because I have no idea how to use it (I tried a few things, but nothing resulted).  The creator didn't provide documentation or readme, and confirmed they're not interested in providing info when I contacted them, and there was no issues/discussion/wiki.  **If anyone has anything helpful to add to the instructions above from Georg Zeiser**, after looking at the code, do please add any documentation/info that you'd like to offer in one of the areas below, or by pull request to this Readme, I think it would be helpful to people.

To make any info contributions as easy as possible, I've activated:
- **Discussions** area
- **Issues** area
- Unrestricted **Wiki**

# Virus Scan = Clean

For what it's worth, the packaged exe of the original looks clean in anti-virus.  Though you should be following good practice and always scanning your executables.

# Bio Note
I have no programming skills or understanding though I've contributed to projects in documentation, databases, images/thumbnails, and support.  If I can help you (reader) in some way, or in exchange for documentation of the Demon's Souls Trainer, let me know.
