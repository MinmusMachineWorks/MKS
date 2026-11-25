> **Minmus Machine Works fork.** This is a fork of [UmbraSpaceIndustries/MKS](https://github.com/UmbraSpaceIndustries/MKS),
> based on [gabes-ksp-fixes/MKS-Fixed](https://github.com/gabes-ksp-fixes/MKS-Fixed) (mhoram-kerbin's WOLF
> and editor fixes) plus a few more community fixes. Install it through CKAN as `UKS-MM`, after adding the
> [Minmus Machine Works repository](https://github.com/MinmusMachineWorks/KSP-Mods-CKAN). It replaces the
> official `UKS` package. Releases are built by `.github/workflows/release.yml` from
> `v*.*.*` tags. CKAN metadata lives in `ckan/metadata.json`.
>
> **Building.** The projects use [KSPBuildTools](https://github.com/KSPModdingLibs/KSPBuildTools) and
> build with `dotnet build Source/MKS.sln`. `KolonyTools.dll` lands in
> `FOR_RELEASE/GameData/UmbraSpaceIndustries/MKS/`, and `USI_WOLF.dll` and `WOLFUI.dll` in `.../WOLF/`.
> They aren't committed. KSPBuildTools finds a Steam KSP install by itself. It also needs USITools in
> `GameData/000_USITools/` of that install. If your mods live elsewhere, create a gitignored
> `Directory.Build.props.user` that sets `KSPBT_GameRoot` (the KSP folder with USITools installed) and,
> if needed, `KSPBT_ManagedPath`.

Modular Kolonization System (MKS) 
===

This is the repository for the MKS and OKS mods for [Kerbal Space Program](http://kerbalspaceprogram.com)

MKS and OKS are the original works of RoverDude (GitHub user BobPalmer).  

You can find the official repo for this mod on [Github](https://github.com/UmbraSpaceIndustries/MKS).  Releases, along with other USI products, can be found on [the USI Catalog Page](https://umbraspaceindustries.github.io/UmbraSpaceIndustries/). 

### Supported Mods
(MKS includes additional functionality when these mods are present)
* [USI Life Support](https://forum.kerbalspaceprogram.com/index.php?/topic/105202-13-usi-life-support-050/)
* [TAC Life Support](https://forum.kerbalspaceprogram.com/index.php?/topic/146465-141-tac-life-support-v0139-release-17th-march-2018/)
* [Snacks](https://forum.kerbalspaceprogram.com/index.php?/topic/149604-141-snacks-friendly-simplified-life-support/) via the [E-Z Snack Oven](http://forum.kerbalspaceprogram.com/threads/92309)
* [Extraplanetary Launchpads](http://forum.kerbalspaceprogram.com/threads/59545)

NOTE:  For Life Support Mods (USI, TAC, or Snacks!) it is recommended you only pick one!  USI-LS is the default, and will afford the most support and integration, but TAC-LS and Snacks! are also fully supported.

### Included Plugins/Mods
* [Module Manager](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-141-module-manager-306-marsh-14th-2018-its-dangerous-to-go-alone-take-those-cats-with-you/)
* [Firespitter Core](https://forum.kerbalspaceprogram.com/index.php?/topic/22583-firespitter-propeller-plane-and-helicopter-parts-v71-may-5th-for-ksp-10/&)
* [Community Resource Pack](https://forum.kerbalspaceprogram.com/index.php?/topic/83007-13-community-resource-pack/)
* [Community Category Kit](https://forum.kerbalspaceprogram.com/index.php?/topic/149840-discussion-community-category-kit/)

### Compatible with

* [Connected Living Space](https://forum.kerbalspaceprogram.com/index.php?/topic/109972-131-connected-living-space-v1258-17-mar-2018-localization/) (efficiency extensions)

### FAQ, Documentation, Issues and Pull Requests

Here you can find the [FAQs](https://github.com/UmbraSpaceIndustries/MKS/wiki/FAQ)

There are also [Tutorials](https://github.com/UmbraSpaceIndustries/MKS/wiki/Tutorials)

You can also use GitHub issues to report bugs and provide suggestions, etc.

Pull Requests should be merged into the branch "DEVELOP".

### Download Link

You can download the current version of MKS from [the USI Catalog Page](https://umbraspaceindustries.github.io/UmbraSpaceIndustries/).  Note that for the sake of my own sanity, only the current release version is supported.

### Other Contributors and Thanks!
* PrivateFlip/Cyrik (Orbital Logistics code)
