# Changelog  
  
| modName    | Asteroid Cities (KMAC) by dtobi                             |
| ---------- | ----------------------------------------------------------- |
| license    | CC-BY-ND-4.0+ARR                                            |
| author     | dtobi and zer0Kerbal                                        |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/AsteroidCities)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/AsteroidCities) |
| ckan       | AsteroidCities                                              |

## Version 2.1.99.1-prerelease - `<Spasibo evanisrael>` edition

* Released
  * 05 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
* THIS IS A PRERELEASE
* functionality is limited
  * Dependencies:
    * [Klockheed Martian Ltd (KML)](https://www.curseforge.com/kerbal/ksp-mods/KlockheedMartianLtd)
  * search for `kmac` in editors

### Change Summary 2.1.99.1

* Add Russian (Русский) localization
  * [ru.cfg] - spasibo [evanisrael](https://github.com/evanisrael)
  * [readme-ru.md] - spasibo [evanisrael](https://github.com/evanisrael)
  * [quickstart-ru.md] - spasibo [evanisrael](https://github.com/evanisrael)
* Update documentation

### Changes 2.1.99.1

#### Localization 2.1.99.1

* Add localizations
  * Russian (Русский)
  * [ru.cfg] - spasibo [evanisrael](https://github.com/evanisrael)
  * [readme-ru.md] - spasibo [evanisrael](https://github.com/evanisrael)
  * [quickstart-ru.md] - spasibo [evanisrael](https://github.com/evanisrael)
* closes #46 - Russian (Русский) <ru.cfg>
* updates #38 - Localization - Master

#### Docs 2.1.99.1

* Update
  * [Attribution.md] v1.0.2.0
  * [404.md] v1.0.2.0
  * [Localizations.md] v1.0.2.0
  * [PartsCatalog.md] v1.0.2.0
  * [readme.md] v2.1.99.1
  * [releasenotes.md] v2.1.99.1

#### Status 2.1.99.1

* Issues
  * closes #60 - Asteroid Cities (AC) 2.1.99.1-prerelease `<Spasibo evanisrael>` edition
  * closes #61 - 2.1.99.1 Additional Tasks

---

## Version 2.1.99.0-adoption - `<Thank you dtobi>` edition

* Released
  * 30 May 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * Dependencies:
    * [Klockheed Martian Ltd (KML)](https://www.curseforge.com/kerbal/ksp-mods/KlockheedMartianLtd)
  * search for `kmac` in editors

### Change Summary 2.1.99.0

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

* THIS IS A PRERELEASE
  * Do not use on saves you care about
  * all parts are showing in editor and flight
  * functionality is limited
* Modernized, and localized all five specialized parts
* Compatibility (experimental)
  * [TACS-LS.cfg]
  * [ConnectedLivingSpace.cfg]
  * [KM-AsteroidTools.cfg]

### Changes 2.1.99.0

### Archival Releases 2.1.99.0

* Releases
  * 2.1.0.0-release `<Archival>`
  * 2.0.1.0-release `<Archival>`
  * 2.0.0.0-release `<Archival>`
  * 1.0.0.0-release `<Archival>`
  * 0.5.0.0-release `<Archival>`
  * 0.4.0.0-release `<Archival>`
  * 0.3.1.0-release `<Archival>`
  * 0.3.0.0-release `<Archival>`
  * 0.2.0.0-release `<Archival>`
  * 0.1.1.0-release `<Archival>`

#### Parts 2.1.99.0

* Lint
* Modernize
* Localize
* Done:
  * Nodes
  * inventory
  * DRAG_CUBES
* closes #56 - Part Localization

#### Compatibility 2.1.99.0

* Split out from part configs:
  * [ConnectedLivingSpace.cfg]
  * [TACS-LS.cfg] (experimental)
  * [KM-AsteroidTools.cfg] (experimental)

#### Docs 2.1.99.0

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Parts-Catalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #33 - Create GitHub Pages

#### Hero Logo 2.1.99.0

* Create
* closes #34 - Create HeroLogo.png

#### Asset Updates 2.1.99.0

* create Assets/ folder
* convert from mesh to MODEL
* convert
  * from tga, mbm, and png to dds
  * parts: tga 11.7mb --> dds 6.11mb
  * IVA: tga 5.11mb --> png 1.34mb --> dds 4.0mb
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* update IVA
* closes #36 - Part Asset Updates

#### Localization 2.1.99.0

* create Localization/
  * create [en-us.cfg] v1.0.0.0
  * create [readme.md] v2.1.1.0
  * create [quickstart.md] v1.0.1.0
* closes #35 - Create Localization directory and contents
* closes #39 - English [en-us.cfg]
* updates #38 - Localization - Master

#### Tags 2.1.99.0

* Add
  * [AsteroidCities.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #37 - Create <AsteroidCities.cfg>
* closes #57 - Part Tags

#### Status 2.1.99.0

* Issues
  * closes #29 - Asteroid Cities (AC) 2.1.99.0-adoption `<Thank you dtobi>` edition
  * closes #30 - 2.1.99.0 Create Legal Mumbo Jumbo
  * closes #31 - 2.1.99.0 Create Documentation
  * closes #32 - 2.1.99.0 Create Social Media Presence

---

## Version 2.1(.0.0)

* update [asteroid.cfg] by agisis
* closes #16 - Version 2.1.0.0
* updates #6 - Releases to be archived

---

## Version 2.0.1(.0)

* ? add [asteroid.cfg] by agisis
* closes #15 - Version 2.0.1.1
* closes #6 - Releases to be archived

---

## Version 2.0(.0.0)

* New KM Folder structure
* Compatibility for 0.24
* closes #14 - Version 2.0.0.0
* updates #6 - Releases to be archived

---

## Version 0.5(.0.0)

* Fix for reattachment of grabbers (hopefully)
  * Grabbers should now be attachable multiple times
  * Improved grabber collision meshes for better grabbing
  * Turned Philly and large grabber around so that "control from here" works better
* closes #13 - Version 0.5.0.0
* updates #6 - Releases to be archived

---

## Version 0.4(.0.0)

* Command bunker
* performance fix
* closes #12 - Version 0.4.0.0
* updates #6 - Releases to be archived

---

## Version 0.3.1(.0)

* Hotfix for missing km_lib.dll
* closes #11 - Version 0.3.1.0
* updates #6 - Releases to be archived

---

## Version 0.3(.0.0)

* Resource Generator improvements
  * Resource generator stops when running out of one input resource
  * Resource converter stops when running out pf output resource space
* closes #10 - Version 0.3.0.0
* updates #6 - Releases to be archived

---

## Version 0.2(.0.0)

* Updated conversion rates to avoid magic mass increase
* increased electricity drain.
* closes #9 - Version 0.2.0.0
* updates #6 - Releases to be archived

---

## Version 0.1.1(.0)

* Asteroids now contain
  * Ore
  * Kethane
  * if the plugins are installed.
* The Philly scanner scans for both, too.
* closes #8 - Version 0.1.1.0
* updates #6 - Releases to be archived

## Version 0.1(.0.0)

* Initial release
* by dtobi
* 01 May 2014
* closes #7 - Version 0.1.0.0
* updates #6 - Releases to be archived

---
