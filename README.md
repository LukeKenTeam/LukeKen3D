# Luke Ken 3D Planet Invasion 
[![Click me](doc/banner.png)](https://example.com/target-page)

Luke Ken 3D Planet Invasion is a free, open-source cosmic retro-futuristic first-person shooter (FPS) game, developed also as a data replacement for the Duke Nukem 3D engine. LK itself, is just raw data for the game engine, these assets are provided for use with compatible engines like EDuke32, JFDuke, and Rednukem or the original DOS version. While it shares some similarities with Duke Nukem 3D, LK features its own unique story, characters, concepts and ideas, and is not intended to be a direct clone or emulation of the original game. This project is designed to be fully vanilla-compatible, meaning it can be also played using the DOS port version of the Atomic Edition if so desired. 

# Current status
The project is currently in early alpha stage known as AlphaKen. There's no gameplay as of yet, just assets for now.
Therefore, we have to manually create the binary file, it's a very time consuming process to do, until some script tools are made to build these game files. We appreciate your understanding as we work towards improving and expanding onwards with the project.

# Story 
If you like to learn more about the story, click [Here](https://lukekenteam.github.io/story.html). Please beware it is subject to change over time. 

## Table of Contents

- [Getting Started](#getting-started)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [License](#license)
- [What"Free"Means](#what-free-means)
- [Credit](#credit)
- [Community](#community)

## Getting Started

### Prerequisites

Luke Ken 3D consists of game data only, you'll need to download a compatible engine separately. There are several options to choose from, including RetroDuke, xDuke, EDuke32, JFDuke, and Rednukem.

Please note that not all source ports may work seamlessly with this GRP file (Game Resource Package). For example, EDuke32 based source ports only read hashes, which may require to create a `.groupinfo` text file to define all the hashes for it to read. Hopefully, down the line, this issue can be resolved in the future.

## Installation
First download the GRP (Game Resource Package) file [Here](https://github.com/LukeKenTeam/LukeKen3D/releases)

For EDuke32:
1. Extract the lukeken.grp and LK.grpinfo to your eduke32 source port folder.
3. Run the executable file of EDuke32.
4. Have fun!

Legacy way:
1. Extract the lukeken.grp file to your source port folder.
2. Rename lukeken.grp to duke3d.grp.
3. Run the executable file of your chosen source port.
4. Have fun!

# Compatibility

It does may vary on somethings like mods, Mostly maps should work just fine. We will try to be faithful for compatibility as possible thats our goal. 
If you like to check on what was previously tested click [Here](docs/Compatibility.md) find out more info. 

## Contributing

New contributors are always welcome for Luke Ken 3D project, however, there are certain guidelines that should be followed to ensure the project stays true to its goals of being a free content game. 
Be sure to read our submission guidelines for [here](docs/GUIDELINES.md) to check out more information.

**Submiting work**
If you'd like to contribute to the project:

1. **Join Discord:**
   - Join our Discord server to discuss and showcase your contribution, preferably in the development channels, so we can ensure everything is in check before you proceed to the next steps. Going ahead and doing a pull request without asking first, may mix things up or compromise quality control, it's good to talk with us first. Once everything checks out by us, proceed to step 2.

2. **Fork and make a pull request:**
   - Fork the project repository on GitHub by clicking the "Fork" button, only if you have to do this once if this is your first time.
   - Open Up the GitHub desktop and clone the project to your computer.
   - Now click repository and open show in file explorer.
   - All the files and folders should be displayed, you need to be in the assets folder to add the stuff you have made such as art and sounds, music in those folders. 
   
3. **Make Changes:**
   - Implement and add the desired changes in your forked repository. Remember to provide your name and email in the 'credits' folder, specifying the assets you worked on (e.g., tile0000.txt) with your credentials inside the doc.
   
   - Choose your changes, add comment and submit to origin.

4. **Submit Pull Request:**
   - Go to branch tab.
   - Click on Create Pull Request.
   - It should open up a webpage and allow you to submit a Pull Request.

Please allow us some time to review your contribution. If, for any reason, your work is rejected, please understand that it might not be finished, or there could be an existing issue within your work. If everything is in order, us maintainers will proceed through with the submission. Please note: Avoid making large submissions that might be unfeasible for our project without consulting us first. Such submissions might be rejected. 

Note: If you are using terminal or command line to submit just beaware how you use it. If you have storng understand how it works, feel free to submit work in that method as well.

## License
All assets within the Luke Ken 3D project are covered by a open source license, a licensing model akin to what's used by other popular open-source projects like [Freedoom](https://freedoom.github.io/) and [LibreQuake ](https://librequake.queer.sh/). This license generously permits commercial use of the assets and credits to the people that help with project.

Assets and Project:
- The game assets and project are licensed under the [BSD 3-Clause License](COPYING).

Game Data Dependencies:
- Duke Nukem 3D Test Data is licensed under the [GNU General Public License (GPL) version 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
- Build Engine Formats and .DAT [Build Engine License](http://advsys.net/ken/buildsrc/).

Please review the respective licenses for more details.

However, it's important to keep in mind that while Luke Ken 3D assets and project under a open source license, other data bundled in this project, might have different licensing constraints. For instance, the build engine data cannot be sold for commercial purposes without explicit consent from its creator, Ken Silverman. Which makes hard for us have added to GNU/Linux distributions. We kindly encourage you to thoroughly review the individual licenses of any extra data incorporated into this project before using or distributing it. Rest assured, there shouldn't be any complications as long as you're distributing it for free without any cost. The game will remain on the Luke Ken Team webpage for the time being until something will change. Hopefully, Ken Silverman can reason and understand about what we're doing when it comes to open source content. If there seems to be a misunderstanding with Build Engine related stuff or the license not necessary for that. Do please let us know. Thanks! 

## What "Free" Means

When we speak of free content or software, we refer to the movement in which your freedoms to use, copy, modify, and study a work is not infringed. For example, you may freely use Luke Ken 3D Assets for any purpose you see fit, you may redistribute it to anyone without needing to ask for permission, you may modify it (provided that you do keep the license intact, see COPYING), and you may study it—​for example, to see how a "GRP (Game Resource Package)" and how the game is built. To facilitate this, you can get the full source code for Duke Nukem 3D to understand how the game works.

You may read more about free software at the [GNU](http://www.gnu.org/) and [Free Software Foundation](http://www.fsf.org) websites.

## Credit

Luke Ken 3D Project is made up of submissions from many people all over the globe. All of them, and you, deserve credit! Please do not forget to provide your name and email/contact info when submitting resources.

## Community

We welcome anyone who is interested in the development of Luke Ken to join our Discord community, where you can connect with other fans of the game, share your own mods and levels, and get help and support from other members. Click [here](https://discord.gg/TSFYwTPqUk) to join.
