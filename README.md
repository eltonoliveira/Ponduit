| AppVeyor Overall | AppVeyor Master | AppVeyor Dev | Coveralls.io  | Download |
| :--------------: | :-------------: | :----------: | :-----------: | :--------:|
| [![Build status](https://ci.appveyor.com/api/projects/status/iwmaeig0xi0kgtlf?svg=true)](https://ci.appveyor.com/project/OCram85/ponduit) | [![Build status](https://ci.appveyor.com/api/projects/status/iwmaeig0xi0kgtlf/branch/master?svg=true)](https://ci.appveyor.com/project/OCram85/ponduit/branch/master) | [![Build status](https://ci.appveyor.com/api/projects/status/iwmaeig0xi0kgtlf/branch/dev?svg=true)](https://ci.appveyor.com/project/OCram85/ponduit/branch/dev) | [![Coverage Status](https://coveralls.io/repos/github/OCram85/Ponduit/badge.svg?branch=master)](https://coveralls.io/github/OCram85/Ponduit?branch=master) | [![Download](https://img.shields.io/badge/powershellgallery-Ponduit-blue.svg)](https://www.powershellgallery.com/packages/Ponduit)

General
=======

Ponduit is a simple Powershell based [Phabricator](https://phacility.com/) Conduit Client.
It enables you to interact with all known [Conduit Methods](https://secure.phabricator.com/conduit/).

To get started read the [about_Ponduit](/src/en-US/about_Ponduit.help.txt) page.

Installation
============


PowerShellGallery.com (Recommended Way)
---------------------------------------

* Make sure you use PowerShell 5.0 or higher with `$PSVersionTable`.
* Use the builtin PackageManagement and install with: `Install-Module Ponduit`
* Done. Start exploring the Module with `Import-Module Ponduit ; Get-Command -Module Ponduit`

Manual Way
----------

* Take a look at the [Latest Release](https://github.com/OCram85/Ponduit/releases/latest) page.
* Download the `Ponduit.zip`.
* Unpack the Zip and put it in your Powershell Module path.
  * Don't forget to change the NTFS permission flag in the context menu.
* Start with `Import-Module Ponduit`
