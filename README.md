<!--For a short line, feel free to use the [link text](URL) format. For longer lines, you may want to use the [link text][link reference name], and put the URL after its name in the bottom section with the others.-->

# VR Software Status

Objective: Investigate software such as [these native titles on Steam] to find whether they actually support virtual reality (VR) on Linux. In addition, [Steam Play] whitelisted software will also be tracked. Please post [what issues you have here].

This document is VR-focused, but augmented reality (AR) applications will also be included. (Together, VR and AR are known as XR.)

Make sure to use the latest graphics drivers and Linux kernel available to you. At a minimum, Linux kernel 4.13 with Mesa 18.2 (AMD) or Nvidia version 430.26 is required for the SteamVR beta. For more details on SteamVR for Linux, [click here.]

For unsupported games that may work with [Proton], see [the list on Gitlab] or [the Steam forum thread].

### Confirmed Working

##### Games

* [BallisticNG] - [discussion][ballisticng thread]
* [Balloonatics]
* [Beat Saber] - on Steam Play whitelist
* [BeepSaber](https://github.com/NeoSpark314/BeepSaber) - native Beat Saber alternative using Godot
* [Doom VFR] - on Steam Play whitelist
* [Dungeon Hero]
* [Everspace] - [dev comment][everspace dev]
* [Fake Racing]
* [Half-Life: Alyx] - [announcement][hl alyx announce] - [issues][hl alyx issues]
* [Google Earth VR] - on Steam Play whitelist
* [Groove Gunner]
* [Locomancer]
* [Munch VR] - [announcement][munch vr announce]
* [Neos VR] - [announcement][neos vr post]
* [OpenMW (VR fork)] - [issue][openmw issue]
* [Polynomial 2] - [discussion][polynomial 2 thread]
* [RBDOOM-3-BFG](https://github.com/Codes4Fun/RBDOOM-3-BFG)
* [Serious Sam Fusion 2017](https://store.steampowered.com/app/564310)
* [Serious Sam 3 VR: BFE]
* [Serious Sam VR: The First Encounter] - [dev post][ssvr1post]
* [Serious Sam VR: The Second Encounter]
* [sphereFACE] - [issue](https://gitlab.com/vr-on-linux/VR-on-Linux/issues/2)
* [The Talos Principle VR](https://store.steampowered.com/app/552440/)
* [Universe Sandbox 2] - [discussion][universe sandbox 2 discussion]
* [Vivecraft](http://www.vivecraft.org/)
* [X-Plane] - [discussion][xplane discussion]
* [vkQuakeVR]
* [Zaccaria Pinball](https://store.steampowered.com/app/444930/)
* [ZED] - [dev post][zed-vr]

##### Other Software

* [Beataroni] - Beat Saber mod installer
* [BeatSaberModManager](https://github.com/affederaffe/BeatSaberModManager) - Beat Saber mod installer
* [Bino] - video player with a focus on 3D and VR
* [Blender] - open source 3D graphics software (modeling, animation, etc.)
    * See [Configuring Peripherals] in the Blender Manual
* [Exokit] - [issue](https://gitlab.com/vr-on-linux/VR-on-Linux/issues/3) - VR/AR/XR engine for JavaScript
* [FreeCAD] OpenXR fork - open source CAD modeling software
* [Gaia Sky VR] - [issue](https://gitlab.com/vr-on-linux/VR-on-Linux/issues/4) - 3D universe application
* [Godot] - open source game engine, requires [plugin][godot plugin]
* [libsurvive] - open source Lighthouse tracking system
* [Monado] - [blog post][monado post] - free and open source [OpenXR][openxr] runtime
* [Open Brush] - [Linux builds][openbrush builds] - fork of the open sourced 3D painting app Tilt Brush
* [Overte] - open-source social VR metaverse, non-profit fork of Vircadia
* [ShellSaber] - Beat Saber mod manager written in POSIX-compliant shell script
* [Simula] - VR window manager for Linux that runs on top of Godot
* [SteamVR] - Valve's VR software system
* [SoundStage VR] - [Linux builds][soundstage-linux] - music app
* [Unreal Engine] - proprietary game engine; VR on Linux with 4.16+
* [Vircadia](https://vircadia.com) - [issues](https://gitlab.com/vr-on-linux/VR-on-Linux/issues/13) - open source social VR metaverse, successor of High Fidelity
* [vr-video-player] - play stereoscopic 3D videos (and some non-VR games) on your VR headset
* [xrdesktop] - [Announcement][xrdesktop post] - interact with the Linux desktop in XR

### Confirmed Planned

The developers will try to make a Linux version at some point. May or may not be released.

* [Climbey] - [dev comment][climbey dev]
* [cyubeVR] - [dev post][cyubevr post]
* [Holodance] - [dev comment][holodance dev]
* [Left-Hand Path] - [dev post][left hand post]
* [Legend of Dungeon] - [dev post][legend dev]
* [Pierhead Arcade] - [dev post][pierhead dev]
* [QuiVr] - [dev post][quivr dev]

### Confirmed Not Working (Natively)

* [Distance][distance] - [mod comment][distance thread] (works with Proton)

### Not Currently Planned

Some have great [Proton] compatibility, but are not whitelisted. Others have more mixed results, but may work well. See [the list on Gitlab] or [the Steam forum thread] for more info.

* [5089] - [dev post][5089 post]
* [Budget Cuts 2] - [dev post][bc2 post]
* [Duck Force] - [duck force dev]
* [Job Simulator] - [dev post][job sim post]
* [Legend of Luca] - [dev post][legend luca post]
* [Hot Dogs, Horseshoes, and Hand Grenades] - [dev post][h3vr post]
* [Racket: Nx] - [dev post][racket nx post]
* [Raw Data] - [dev post][raw data post]
* [Sublevel Zero] - [dev post][sublevel zero post]
* [Subnautica] - [dev post][subnautica post]

----

# VR Hardware Status

### Confirmed Working

* HTC Vive/Vive Pro and Valve Index via [SteamVR] (development beta)
    * [Bluetooth does not work]
        * [No power management for base stations]
          * v1 (Vive) workaround: [lhctrl] (for Vive)
          * v2 (Index, Vive Pro): [Lighthouse PM] (Android), [lh2ctrl], [lighthouse-v2-manager]
          * v1 or v2: [steamvr_utils](https://github.com/DavidRisch/steamvr_utils)
    * [Index camera does not work]
* [Vive Trackers](https://www.vive.com/us/accessory/tracker3/)
* [Tundra Trackers](https://tundra-labs.com/)
* [SlimeVR Full-Body Tracker](https://www.crowdsupply.com/slimevr/slimevr-full-body-tracker)
* Oculus Rift development kits (DK1, DK2) - [ArchWiki: Oculus Rift]

### Unofficial OpenHMD Support

[These currently lack positional tracking functionality], and not as many games support OpenHMD yet.

* Oculus Rift S
* Microsoft Mixed Reality
* PSVR

These have experimental positional tracking support [from a development branch].

* Oculus Rift CV1
* Oculus Rift DK2

Also check out [Monado], the free and open source [OpenXR] implementation. It relies on OpenHMD for some devices.

If you want official Linux support for the Oculus Rift, [add your vote here]. If you want, leave a nice comment, too.

### Unofficial ALVR Support (Experimental)

Some Oculus headsets are supported by [ALVR](https://alvr-org.github.io/) (Air Light VR).

> Stream VR games from your PC to your headset via Wi-Fi.\
> ALVR uses technologies like Asynchronous Timewarp and Fixed Foveated Rendering for a smoother experience.\
> All games that work with an Oculus Rift (s) should work with ALVR. 

> Linux support is still in beta. To be able to make audio work or run ALVR at all you may need advanced knowledge of your distro for debugging or building from source.

ALVR currently supports:

* Oculus Quest 1/2/Pro
* Pico 4/Neo 3
* Vive Focus 3/XR Elite
* YVR 1/2

### Graphics Cards 

You should try to get the latest graphics drivers that are available. For Nvidia users, have at least the NVIDIA 470.42.01 driver installed, available since June 22, 2021. For AMD users, have at least Mesa 18.2 (September 2018). Intel graphics are not currently supported by SteamVR.

----

# Troubleshooting

## SteamVR

### Rainbow pixels at the edge of my viewport (AMDGPU)

SteamVR only renders what can actually be seen by the player. This results in two ovals being drawn on the HMD. SteamVR does not touch the outside of those ovals. That results in random pixels from the VRAM segment the frame buffer was allocated on.
You can probably see these if you move your eyes quick enough and are looking at a dark scene in VR.

You can tell the RADV driver to always zero the frame buffer to avoid this. I am not sure if this results in a performance penalty or not.

**Fix**
- Add this environment variable to the launch options of SteamVR: `RADV_DEBUG=zerovram`
  - NOTE: You can add multiple options to `RADV_DEBUG` by separating them with a comma (`,`). Example: `RADV_DEBUG=zerovram,nodcc`

### SteamVR doesn't start on Wayland

If you have environment variables that force Qt or SDL apps to run in Wayland mode, SteamVR might not start at all.

**Fix**
- Add these environment variables to the launch options of SteamVR: `QT_QPA_PLATFORM=xcb SDL_VIDEODRIVER=x11`

### SteamVR does not use direct mode on Wayland (window appears on monitor)

If this has never worked for you on Wayland, make sure your compositor supports the `wp_drm_lease_device_v1` protocol. (As of writing both Sway and KWin support it)

**Fix**
- Use a compositor that supports `wp_drm_lease_device_v1`
- Make sure your XWayland version supports `wp_drm_lease_device_v1` (X.Org 22.1.0+)

### SteamVR *occasionally* does not use direct mode on Wayland (window appears on monitor)

Sometimes SteamVR fails to use direct mode. This is probably because the last instance didn't release its lease on your HMD. You can kill `XWayland` and try again (Sway automatically restarts it when needed)

If your HMD is listed in the output of `xrandr`, it probably means that it's available for lease.

**Fix**
- Restart XWayland
- Alternatively restart your compositor

### No microphone input from HMD

The microphone of the Valve Index is kinda finnicky. Your best bet is to use PipeWire here.
PulseAudio can be made to work, if you figure out the correct sample-rate and stuff.

**Fix**
- Use PipeWire
- (Maybe) Make sure you have selected the corresponding HDMI output (the Index won't capture the microphone otherwise?)

### Double-vision when moving head

Asynchronous reprojection is broken in SteamVR on Linux. If games generate enough frames, you won't see this. But if the games framerate is too low, you will probably experience this.
There is no real fix, as disabling asynchronous reprojection will just reduce the perceived framerate on your HMD.

**Fix**
- Disable async reprojection (degrades perceived performance) by setting `"enableLinuxVulkanAsync" : false` under the `steamvr` section at `~/.steam/steam/config/steamvr.vrsettings`

### Graphics artifacts in SteamVR and in overlays (AMDGPU)

[Upstream issue][overlay wobble]

**Fix**
- Add this environment variable to the launch options of SteamVR: `RADV_DEBUG=nodcc`
  - NOTE: You can add multiple options to `RADV_DEBUG` by separating them with a comma (`,`). Example: `RADV_DEBUG=zerovram,nodcc`

### Overlays are wobbling/jittering

[Upstream issue][overlay wobble]

This is a SteamVR bug and it can't really be fixed from the outside.

There is some discussion in [this Reddit thread][overlay wobble workarounds] about some workarounds, but they can cause issues with some games.

----

# Acknowledgements

Many thanks to:

* All [contributors]
* Steam user [Teq] for compiling [the old list] (please don't post on it)
* Valve for [SteamVR] for Linux and [the forum]
* Reddit communities [/r/linux_gaming] and [/r/virtualreality_linux]
* IRC channel [#vronlinux] on [irc.libera.chat](https://libera.chat/)
* Acenomad for [LeagueofLinux.org](https://leagueoflinux.org/) which [VRonLinux.gitlab.io](https://VRonLinux.gitlab.io/) is based on
* Players like you

<!--Web Addresses (will not display)-->

  [these native titles on Steam]: https://store.steampowered.com/search?vrsupport=401%2C402&os=linux
  [click here.]: https://github.com/ValveSoftware/SteamVR-for-Linux
  [Steam Play]: https://steamcommunity.com/games/221410/announcements/detail/1696055855739350561
  [what issues you have here]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/issues
  [Proton]: https://github.com/ValveSoftware/Proton/
  [the list on Gitlab]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/tree/master/Proton
  [the Steam forum thread]: https://steamcommunity.com/app/250820/discussions/5/4839692156569764298/

<!--Confirmed Working: Games-->

  [BallisticNG]: https://store.steampowered.com/app/473770
  [ballisticng thread]: https://steamcommunity.com/app/473770/discussions/9/3288067088117151530/
  [Balloonatics]: https://store.steampowered.com/app/744600/Balloonatics/
  [Beat Saber]: https://store.steampowered.com/app/620980
  [Doom VFR]: https://store.steampowered.com/app/650000
  [Dota 2]: https://store.steampowered.com/app/570/
  [Dungeon Hero]: https://store.steampowered.com/app/366810
  [Everspace]: https://store.steampowered.com/app/396750
  [everspace dev]: https://steamcommunity.com/app/396750/discussions/0/1290691308569316537/?ctp=7#c3223871682611119274
  [Fake Racing]: https://store.steampowered.com/app/1481600/Fake_Racing/
  [Google Earth VR]: https://store.steampowered.com/app/348250
  [Half-Life: Alyx]: https://store.steampowered.com/app/546560/HalfLife_Alyx/
  [hl alyx announce]: https://steamcommunity.com/games/546560/announcements/detail/3758762298552654078
  [hl alyx issues]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/issues/?search=Alyx&sort=title_asc&state=opened
  [Locomancer]: https://store.steampowered.com/app/490250/
  [Munch VR]: https://store.steampowered.com/app/549000
  [munch vr announce]: https://steamcommunity.com/games/549000/announcements/detail/254855783331915882
  [Neos VR]: https://store.steampowered.com/app/740250/Neos_VR/
  [neos vr post]: https://store.steampowered.com/newshub/app/740250/view/3300515414498852519
  [OpenMW (VR fork)]: https://gitlab.com/madsbuvi/openmw
  [openmw issue]: https://gitlab.com/madsbuvi/openmw/-/issues/33#note_441945362
  [Polynomial 2]: https://store.steampowered.com/app/379420
  [polynomial 2 thread]: https://steamcommunity.com/app/379420/discussions/0/135512305401923487/?tscn=1501357291#c1471966894875192367
  [Serious Sam 3 VR: BFE]: https://store.steampowered.com/app/567670
  [Serious Sam VR: The First Encounter]: https://store.steampowered.com/app/552450
  [ssvr1post]: https://steamcommunity.com/games/552450/announcements/detail/508182627702316801
  [Serious Sam VR: The Second Encounter]: https://store.steampowered.com/app/552460
  [SphereFACE]: https://store.steampowered.com/app/485680
  [vkQuakeVR]: https://github.com/VsevolodGolovanov/vkQuakeVR
  [X-Plane]: https://store.steampowered.com/app/269950
  [xplane discussion]: https://forums.x-plane.org/index.php?/forums/topic/157332-xplane-vr-on-linux/
  [Universe sandbox 2]: https://store.steampowered.com/app/230290
  [universe sandbox 2 discussion]: https://steamcommunity.com/app/230290/discussions/0/1488866180597515211/?ctp=2#c2590022385666315727
  [ZED]: https://store.steampowered.com/app/953370/ZED/
  [zed-vr]: https://www.reddit.com/r/linux_gaming/comments/c5ry16/zed_releases_for_linux_today_this_game_was/

<!--Confirmed Working: Other Software-->

  [Beataroni]: https://github.com/geefr/beatsaber-linux-goodies/tree/live/Beataroni
  [Bino]: https://bino3d.org
  [Blender]: https://www.blender.org/
  [Configuring Peripherals]: https://docs.blender.org/manual/en/latest/getting_started/configuration/hardware.html#hardware-head-mounted-displays
  [Exokit]: https://github.com/webmixedreality/exokit
  [FreeCAD]: https://github.com/kwahoo2/FreeCAD/releases
  [Gaia Sky VR]: https://gitlab.com/langurmonkey/gaiasky/tree/vr#readme
  [Godot]: https://godotengine.org/
  [godot plugin]: https://github.com/GodotVR/godot_openvr
  [libsurvive]: https://github.com/cntools/libsurvive
  [Monado]: https://monado.dev
  [monado post]: https://www.collabora.com/news-and-blog/news-and-events/introducing-monado.html
  [OpenXR]: https://www.khronos.org/openxr/
  [Open Brush]: https://github.com/icosa-gallery/open-brush#readme
  [openbrush builds]: https://openbrush.itch.io/openbrush
  [Overte]: https://overte.org
  [ShellSaber]: https://github.com/Ominitay/ShellSaber
  [Simula]: https://github.com/SimulaVR/Simula
  [SoundStage VR]: https://github.com/ChristophHaag/soundstagevr
  [soundstage-linux]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/issues/5#note_93726156
  [Unity XR]: https://github.com/ValveSoftware/unity-xr-plugin/issues?q=is%3Aissue+linux+is%3Aopen
  [Unreal Engine]: https://www.unrealengine.com/
  [vr-video-player]: https://git.dec05eba.com/vr-video-player/about/
  [xrdesktop]: https://gitlab.freedesktop.org/xrdesktop/xrdesktop
  [xrdesktop post]: https://www.collabora.com/news-and-blog/news-and-events/moving-the-linux-desktop-to-another-reality.html

<!--Confirmed Planned-->

  [Climbey]: https://store.steampowered.com/app/520010
  [climbey dev]: https://steamcommunity.com/app/520010/discussions/0/133257959063050510/#c1368380934259432022
  [CyubeVR]: https://store.steampowered.com/app/619500
  [cyubevr post]: https://steamcommunity.com/games/619500/announcements/detail/1699428479882614708/
  [Duck Force]: https://store.steampowered.com/app/511690
  [duck force dev]: https://steamcommunity.com/app/511690/discussions/0/343785574533821511/#c1290690926869411890
  [Groove Gunner]: https://store.steampowered.com/app/976930
  [Holodance]: https://store.steampowered.com/app/422860
  [holodance dev]: https://steamcommunity.com/app/422860/discussions/0/1697167355224768144/#c1697167355224998756
  [Left-Hand Path]: https://store.steampowered.com/app/488760
  [left hand post]: https://reddit.com/r/Vive/comments/7c1kmi/l/dpmwb4o/?context=3
  [Legend of Dungeon]: https://store.steampowered.com/app/238280
  [legend dev]: https://steamcommunity.com/app/238280/discussions/0/135509823662970415/
  [Pierhead Arcade]: https://store.steampowered.com/app/435490
  [pierhead dev]: https://steamcommunity.com/app/435490/discussions/0/133258593403413970/?tscn=1489091768
  [QuiVR]: https://store.steampowered.com/app/489380
  [quivr dev]: https://steamcommunity.com/app/489380/discussions/0/133258092240841267/?tscn=1487964739#c133258092241433588

<!--Confirmed Not Working-->

  [Distance]: https://store.steampowered.com/app/233610
  [distance thread]: https://steamcommunity.com/app/233610/discussions/0/135512305401859168/#c2949168687313272972
  
<!--Not Currently Planned-->

  [5089]: https://store.steampowered.com/app/414510
  [5089 post]: https://steamcommunity.com/app/414510/discussions/0/458606877328345110/?tscn=1488516436
  [Budget Cuts 2]: https://store.steampowered.com/app/1092430/
  [bc2 post]: https://steamcommunity.com/app/1092430/discussions/0/1693843461177999079/#c1738882605425299335
  [Job Simulator]: https://store.steampowered.com/app/448280/
  [job sim post]: https://steamcommunity.com/app/448280/discussions/0/412449508293339269/#c135509823665930598
  [Legend of Luca]: https://store.steampowered.com/app/433600/
  [legend luca post]: https://steamcommunity.com/app/433600/discussions/0/135511027315876295/?tscn=1492031383
  [Hot Dogs, Horseshoes, and Hand Grenades]: https://store.steampowered.com/app/450540/
  [h3vr post]: https://www.reddit.com/r/H3VR/comments/5vj1ws/linux_support
  [Racket: Nx]: https://store.steampowered.com/app/428080/
  [racket nx post]: https://steamcommunity.com/app/428080/discussions/0/133258593391051295/
  [Raw Data]: https://store.steampowered.com/app/436320/
  [raw data post]: https://steamcommunity.com/app/436320/discussions/0/144513248274232587/?tscn=1488917004
  [Sublevel Zero]: https://store.steampowered.com/app/327880/
  [sublevel zero post]: https://steamcommunity.com/app/327880/discussions/0/412447613577448648/?tscn=1488620416
  [Subnautica]: https://store.steampowered.com/app/264710/
  [subnautica post]: https://steamcommunity.com/app/264710/discussions/0/490123938436996887/
  [Tilt Brush]: https://store.steampowered.com/app/327140/
  [tilt brush post]: https://www.phoronix.com/forums/forum/software/linux-gaming/934616-trying-the-steamvr-beta-on-linux-feels-more-like-an-early-alpha?p=934623#post934623

<!--VR Hardware Status-->

  [No power management for base stations]: https://github.com/ValveSoftware/SteamVR-for-Linux/issues/320
  [lhctrl]: https://github.com/risa2000/lhctrl
  [lh2ctrl]: https://github.com/risa2000/lh2ctrl
  [Lighthouse PM]: https://github.com/jeroen1602/lighthouse_pm
  [lighthouse-v2-manager]: https://github.com/nouser2013/lighthouse-v2-manager
  [Bluetooth does not work]: https://github.com/ValveSoftware/SteamVR-for-Linux/issues/96
  [Index camera does not work]: https://github.com/ValveSoftware/SteamVR-for-Linux/issues/231
  [ArchWiki: Oculus Rift]: https://wiki.archlinux.org/index.php/Oculus_Rift
  [These currently lack positional tracking functionality]: http://www.openhmd.net/index.php/devices/
  [from a development branch]: https://github.com/thaytan/OpenHMD/tree/rift-kalman-filter
  [add your vote here]: https://oculus.uservoice.com/forums/918556-oculus-rift-s-and-rift/suggestions/32672992-add-linux-support
  
<!--SteamVR issues-->
  [overlay wobble]: https://github.com/ValveSoftware/SteamVR-for-Linux/issues/395
  [overlay wobble workarounds]: https://www.reddit.com/r/virtualreality_linux/comments/yucy6i/steamvr_flickering_with_asyn_reprojection_solved/

<!--Acknowledgements-->

  [contributors]: https://gitlab.com/vr-on-linux/VR-on-Linux/-/graphs/master?ref_type=heads
  [Teq]: https://steamcommunity.com/id/tangoechoquebec
  [the old list]: https://steamcommunity.com/app/250820/discussions/5/133257959064016658/
  [SteamVR]: https://github.com/ValveSoftware/SteamVR-for-Linux
  [the forum]: https://steamcommunity.com/app/250820/discussions/5/
  [/r/linux_gaming]: https://www.reddit.com/r/linux_gaming
  [/r/virtualreality_linux]: https://www.reddit.com/r/virtualreality_linux
  [#vronlinux]: https://web.libera.chat/#vronlinux
