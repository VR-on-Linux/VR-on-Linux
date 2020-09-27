<!--If it's a short line, feel free to use the [link text](URL) format.
For longer lines, please use the [link text][link reference name], and
put the URL after its name in the bottom section with the others.-->

# VR Software Status

Objective: Investigate software such as 
[these **native** titles on Steam][Steam store link] to find whether they 
actually support virtual reality (VR) on Linux. In addition, [Steam Play]
whitelisted [software] will also be tracked. Please post 
[what issues you have here][issues].

This document is VR-focused, but augmented reality (AR) applications will also
be included. (Together, VR and AR are known as XR.)

Make sure to use the latest graphics drivers and Linux kernel available to you.
At a minimum, Linux kernel 4.13 with Mesa 18.2 (AMD) or Nvidia version 430.26 is 
required for the SteamVR beta. Linux kernel 4.15 is recommended. For more
details on SteamVR, [click here.][steamvr linux github]

Also check out the [VR tag on ProtonDB][protondb tag] for games not listed here 
that may work with [Proton][proton].

### Confirmed Working

##### Games

* [BallisticNG][ballisticng] - [discussion][ballisticng thread]
* [Balloonatics][balloonatics]
* [Beat Saber][beat saber] - on Steam Play whitelist
* [DOTA2][dota2]    
* [Doom VFR][doom vfr] - on Steam Play whitelist
* [Dungeon Hero][dungeon hero]
* [Everspace][everspace] - [dev comment][everspace dev]
* [Half-Life: Alyx][hl alyx] - [announcement][hl alyx announce] - [issue](#11)
* ~~[High Fidelity][high fidelity]~~ ([shut down](#14), see Vircadia below)
* [Google Earth VR][google earth vr]  - on Steam Play whitelist
* [Locomancer][locomancer]
* [Munch VR][munch vr] - [announcement][munch vr announce]
* [Neos VR][neos vr] - [announcement][neos vr post]
* [Polynomial 2][polynomial 2] - [discussion][polynomial 2 thread]
* [RBDOOM-3-BFG](https://github.com/Codes4Fun/RBDOOM-3-BFG)
* [Serious Sam Fusion 2017](https://store.steampowered.com/app/564310)
* [Serious Sam 3 VR: BFE][serious sam 3]
* [Serious Sam VR: The First Encounter][serious sam vr1] - [dev post][ssvr1post]
* [Serious Sam VR: The Second Encounter][serious sam vr2]
* [sphereFACE][sphereface] - [issue](#2)
* [The Talos Principle VR](https://store.steampowered.com/app/552440/)
* [Universe Sandbox 2][universe sandbox 2] - 
  [discussion][universe sandbox 2 discussion]
* [Vivecraft](http://www.vivecraft.org/)
* [X-Plane 11.26][xplane 11.26] - [discussion][xplane discussion]
* [vkQuakeVR][vkquakevr]
* [Zaccaria Pinball](https://store.steampowered.com/app/444930/)
* [ZED][zed] - [dev post][zed-vr]

##### Other Software

* [Exokit][exokit] - [issue](#3) - VR/AR/XR engine for JavaScript
* [Gaia Sky VR][gaia sky vr] - [issue](#4) - 3D universe application
* [Godot][godot] - open source game engine, requires [plugin][godot plugin]
* [Monado][monado] - [blog post][monado post] - free and open source
  [OpenXR][openxr] runtime
* [SteamVR][steamvr linux github] - Valve's VR software system
* [SoundStage VR][soundstage vr] - [Linux builds][soundstage-linux] - music app
* [Unity][unity] - proprietary game engine; OpenVR works on Linux since 2017.3
* [Unreal Engine][unreal] - proprietary game engine; VR on Linux with 4.16+
* [Vircadia](https://vircadia.com) - [issues](#13) - open-source social VR 
  metaverse, successor of High Fidelity
* [vr-video-player][vr-video] - play stereoscopic 3D videos (and some non-VR
  games) on your VR headset
* [xrdesktop][xrdesktop] - [Announcement][xrdesktop post] - interact with the
  Linux desktop in XR

### Confirmed Planned

The developers will try to make a Linux version at some point. May or may not be
released.

* [Climbey][climbey] - [dev comment][climbey dev]
* [cyubeVR][cyubevr] - [dev post][cyubevr post]
* [Groove Gunner][groove gunner] - [dev comment][groove gunner dev]
* [Holodance][holodance] - [dev comment][holodance dev]
* [Left-Hand Path][left hand path] - [dev post][left hand post]
* [Legend of Dungeon][legend of dungeon] - [dev post][legend dev]
* [Pierhead Arcade][pierhead] - [dev post][pierhead dev]
* [QuiVr][quivr] - [dev post][quivr dev]
* [Till Dawn][till dawn]

### Confirmed Not Working (Natively)

No developer response yet.

* [Distance][distance] - [mod comment][distance thread]

### Not Currently Planned

Some have excellent (Platinum) [Proton][proton] compatibility, but are not 
[whitelisted][whitelist]. Others have more "mixed" results, but often work well.

* [5089][5089 post]
* [Accounting (Legacy)][accounting post] (Accounting+: [Platinum][accounting+])
* [Budget Cuts 2][bc2 post]
* [Duck Force][duck force dev]
* [Job Simulator][job sim post] ([Platinum][job sim protondb])
* [Legend of Luca][legend luca post]
* [Hot Dogs, Horseshoes, and Hand Grenades][h3vr post] ([mixed][h3vr protondb])
* [Racket: Nx][racket nx post] ([mixed](https://www.protondb.com/app/428080))
* [Raw Data][raw data post]
* [Sublevel Zero][sublevel zero post]
* [Subnautica][subnautica post]
* [Tilt Brush][tilt brush post]

----

# VR Hardware Status

### Confirmed Working

* HTC Vive/Vive Pro and Valve Index via SteamVR - 
  [SteamVR for Linux Github][steamvr linux github] (development beta)
* Oculus Rift development kits (DK1, DK2) - [ArchWiki][archwiki rift]

### Unofficial OpenHMD Support

[These currently lack positional tracking functionality][openhmd], and not as
many games support OpenHMD yet.

* Microsoft Mixed Reality
* Oculus Rift
* PSVR
* Samsung GearVR

Also check out [Monado][monado], the free and open source [OpenXR][openxr]
implementation. It relies on OpenHMD for some devices.

If you want official Linux support for the Oculus Rift, [add your vote 
here.][rift vote] If you want, leave a comment, too (but be nice!)

----

# Acknowledgements

* Steam user [Teq][teq] for compiling [the original list here][old list]
* Valve for [SteamVR for Linux][steamvr linux github] and [the forum][forum]
* Players like you

<!--Web Addresses (will not display)-->

  [Steam store link]: https://store.steampowered.com/search?vrsupport=401%2C402&os=linux
  [Steam Play]: https://steamcommunity.com/games/221410/announcements/detail/1696055855739350561
  [software]: https://www.protondb.com/explore?page=0&selectedFilters=userTags&selectedFilters=whitelisted&selectedTags=VR
  [issues]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/issues
  [protondb tag]: https://www.protondb.com/explore?selectedFilters=userTags&selectedTags=VR
  [proton]: https://github.com/ValveSoftware/Proton/
<!--Confirmed Working: Games-->
  [ballisticng]: https://store.steampowered.com/app/473770
  [ballisticng thread]: https://steamcommunity.com/app/473770/discussions/9/3288067088117151530/
  [balloonatics]: https://store.steampowered.com/app/744600/Balloonatics/
  [beat saber]: https://store.steampowered.com/app/620980
  [doom vfr]: https://store.steampowered.com/app/650000
  [dota2]: https://store.steampowered.com/app/570/
  [dungeon hero]: https://store.steampowered.com/app/366810
  [everspace]: https://store.steampowered.com/app/396750
  [everspace dev]: https://steamcommunity.com/app/396750/discussions/0/1290691308569316537/?ctp=7#c3223871682611119274
  [google earth vr]: https://store.steampowered.com/app/348250
  [hl alyx]: https://store.steampowered.com/app/546560/HalfLife_Alyx/
  [hl alyx announce]: https://steamcommunity.com/games/546560/announcements/detail/3758762298552654078
  [high fidelity]: https://store.steampowered.com/app/390540
  [hifi linux]: https://github.com/ChristophHaag/hifi
  [locomancer]: https://store.steampowered.com/app/490250/
  [munch vr]: https://store.steampowered.com/app/549000
  [munch vr announce]: https://steamcommunity.com/games/549000/announcements/detail/254855783331915882
  [neos vr]: https://store.steampowered.com/app/740250/Neos_VR/
  [neos vr post]: https://store.steampowered.com/newshub/app/740250/view/3300515414498852519
  [polynomial 2]: https://store.steampowered.com/app/379420
  [polynomial 2 thread]: https://steamcommunity.com/app/379420/discussions/0/135512305401923487/?tscn=1501357291#c1471966894875192367
  [serious sam 3]: https://store.steampowered.com/app/567670
  [serious sam vr1]: https://store.steampowered.com/app/552450
  [ssvr1post]: https://steamcommunity.com/games/552450/announcements/detail/508182627702316801
  [serious sam vr2]: https://store.steampowered.com/app/552460
  [sphereface]: https://store.steampowered.com/app/485680
  [vkquakevr]: https://github.com/VsevolodGolovanov/vkQuakeVR
  [xplane 11.26]: https://store.steampowered.com/app/269950
  [xplane discussion]: https://forums.x-plane.org/index.php?/forums/topic/157332-xplane-vr-on-linux/
  [universe sandbox 2]: https://store.steampowered.com/app/230290
  [universe sandbox 2 discussion]: https://steamcommunity.com/app/230290/discussions/0/1488866180597515211/?ctp=2#c2590022385666315727
  [zed]: https://store.steampowered.com/app/953370/ZED/
  [zed-vr]: https://www.reddit.com/r/linux_gaming/comments/c5ry16/zed_releases_for_linux_today_this_game_was/
<!--Confirmed Working: Other Software-->
  [exokit]: https://github.com/webmixedreality/exokit
  [gaia sky vr]: https://gitlab.com/langurmonkey/gaiasky/tree/vr#readme
  [godot]: https://godotengine.org/
  [godot plugin]: https://github.com/GodotVR/godot_openvr
  [monado]: https://monado.dev
  [monado post]: https://www.collabora.com/news-and-blog/news-and-events/introducing-monado.html
  [openxr]: https://www.khronos.org/openxr/
  [soundstage vr]: https://github.com/ChristophHaag/soundstagevr
  [soundstage-linux]: /issues/5#note_93726156
  [unity]: https://unity.com/
  [unreal]: https://www.unrealengine.com/
  [vr-video]: https://git.dec05eba.com/vr-video-player/about/
  [xrdesktop]: https://gitlab.freedesktop.org/xrdesktop/xrdesktop
  [xrdesktop post]: https://www.collabora.com/news-and-blog/news-and-events/moving-the-linux-desktop-to-another-reality.html
<!--Confirmed Planned-->
  [climbey]: https://store.steampowered.com/app/520010
  [climbey dev]: https://steamcommunity.com/app/520010/discussions/0/133257959063050510/#c1368380934259432022
  [cyubevr]: https://store.steampowered.com/app/619500
  [cyubevr post]: https://steamcommunity.com/games/619500/announcements/detail/1699428479882614708/
  [duck force]: https://store.steampowered.com/app/511690
  [duck force dev]: https://steamcommunity.com/app/511690/discussions/0/343785574533821511/#c1290690926869411890
  [groove gunner]:https://store.steampowered.com/app/976930
  [groove gunner dev]: https://www.gamingonlinux.com/articles/vr-rhythm-game-groove-gunner-looks-insane-and-its-coming-to-linux.14511
  [holodance]: https://store.steampowered.com/app/422860
  [holodance dev]: https://steamcommunity.com/app/422860/discussions/0/1697167355224768144/#c1697167355224998756
  [left hand path]: https://store.steampowered.com/app/488760
  [left hand post]: https://reddit.com/r/Vive/comments/7c1kmi/l/dpmwb4o/?context=3
  [legend of dungeon]: https://store.steampowered.com/app/238280
  [legend dev]: https://steamcommunity.com/app/238280/discussions/0/135509823662970415/
  [pierhead]: https://store.steampowered.com/app/435490
  [pierhead dev]: https://steamcommunity.com/app/435490/discussions/0/133258593403413970/?tscn=1489091768
  [quivr]: https://store.steampowered.com/app/489380
  [quivr dev]: https://steamcommunity.com/app/489380/discussions/0/133258092240841267/?tscn=1487964739#c133258092241433588
  [till dawn]: http://isenmann.blogspot.de/2017/08/till-dawn-first-pre-alpha-version.html
<!--Confirmed Not Working-->
  [distance]: https://store.steampowered.com/app/233610
  [distance thread]: https://steamcommunity.com/app/233610/discussions/0/135512305401859168/#c2949168687313272972
<!--Not Currently Planned-->
  [5089 post]: https://steamcommunity.com/app/414510/discussions/0/458606877328345110/?tscn=1488516436
  [accounting post]: https://steamcommunity.com/app/518580/discussions/0/133258092241829803/
  [accounting+]: https://www.protondb.com/app/927270
  [bc2 post]: https://steamcommunity.com/app/1092430/discussions/0/1693843461177999079/#c1738882605425299335
  [job sim post]: https://steamcommunity.com/app/448280/discussions/0/412449508293339269/#c135509823665930598
  [job sim protondb]: https://www.protondb.com/app/448280
  [legend luca post]: https://steamcommunity.com/app/433600/discussions/0/135511027315876295/?tscn=1492031383
  [h3vr post]: https://www.reddit.com/r/H3VR/comments/5vj1ws/linux_support
  [h3vr protondb]: https://www.protondb.com/app/450540
  [racket nx post]: https://steamcommunity.com/app/428080/discussions/0/133258593391051295/
  [raw data post]: https://steamcommunity.com/app/436320/discussions/0/144513248274232587/?tscn=1488917004
  [sublevel zero post]: https://steamcommunity.com/app/327880/discussions/0/412447613577448648/?tscn=1488620416
  [subnautica post]: https://steamcommunity.com/app/264710/discussions/0/490123938436996887/
  [tilt brush post]: https://www.phoronix.com/forums/forum/software/linux-gaming/934616-trying-the-steamvr-beta-on-linux-feels-more-like-an-early-alpha?p=934623#post934623
<!--VR Hardware Status-->
  [steamvr linux github]: https://github.com/ValveSoftware/SteamVR-for-Linux
  [archwiki rift]: https://wiki.archlinux.org/index.php/Oculus_Rift
  [openhmd]: http://www.openhmd.net/index.php/devices/
  [rift vote]: https://oculus.uservoice.com/forums/918556-oculus-rift-s-and-rift/suggestions/32672992-add-linux-support
<!--Acknowledgements-->
  [teq]: https://steamcommunity.com/id/toq
  [old list]: https://steamcommunity.com/app/250820/discussions/5/133257959064016658/
  [forum]: https://steamcommunity.com/app/250820/discussions/5/
