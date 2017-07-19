# Funceble

> A script to check domains or IP accessibility.

[![license](https://img.shields.io/github/license/funilrys/funceble.svg)](https://github.com/funilrys/funceble/blob/master/LICENSE) [![GitHub tag](https://img.shields.io/github/tag/funilrys/funceble.svg)](https://github.com/funilrys/funceble/tags) [![GitHub release](https://img.shields.io/github/release/funilrys/funceble.svg)](https://github.com/funilrys/funceble/releases/latest)

[![GitHub issues open](https://img.shields.io/github/issues/funilrys/funceble.svg)]() [![GitHub closed issues](https://img.shields.io/github/issues-closed/funilrys/funceble.svg)](https://github.com/funilrys/)

[![Github file size](https://img.shields.io/github/size/funilrys/funceble/funceble.svg)](https://github.com/funilrys/funceble/blob/master/funceble)

The main idea was to create a script that can check if a given domain, a `hosts` file or a **list of domains** are/is **ACTIVE** or **INACTIVE**. And, in between, if wanted, **generate a `hosts` file** based on the results.

Have any question? Fill a new issue and I'll do my best to answer as soon as possible.

## :book: Wiki as place to be :star2::star2::star2:

Want to know more about **Funceble** ? All information to know are under the [wiki](https://github.com/funilrys/funceble/wiki)! You can also contribute there if you want! :smile:

You can get a copy of the wiki with the following:

```shell
git clone https://github.com/funilrys/funceble.wiki.git
```

## Features

- Read an existing `hosts`file and check every domain present into it.
- Change/set timeout for `whois`
- Deactivate logs
- Deactivate the production of unified results
- Silent mode available
- Show on screen

  - The status of a given domain is **ACTIVE**, **INACTIVE** or **INVALID** (live update)
  - The execution time of the script (at the end)
  - The percentage of **ACTIVE**, **INACTIVE** and **INVALID** (at the end)

- Save on single file

  - Result of execution (live update)
  - Execution time (at the end)
  - The percentage of **ACTIVE**, **INACTIVE** and **INVALID** (at the end)

- Save on separated files (when needed)

  - Logs of encountered error(s)
  - **ACTIVE** domain
  - **INACTIVE** domain
  - **INVALID** domain

- Generate `hosts` file

  - With custom IP
  - ONLY with **ACTIVE** domains

## Valuable links

They updated their hosts file or blocklist with the help of [Funceble](https://github.com/funilrys/funceble/) or [dead-hosts](https://github.com/funilrys/dead-hosts).

Repo / List Name                         | Author                                             | Repository / Website                                                                       | Raw
---------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------
Badd-Boyz-Hosts                          | [Mitchell Krog](https://github.com/mitchellkrogza) | [Repository](https://github.com/mitchellkrogza/Badd-Boyz-Hosts)                            | [Raw](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/PULL_REQUESTS/domains.txt)
KADhosts                                 | [KAD](https://github.com/azet12)                   | [Repository](https://github.com/azet12/KADhosts)                                           | [Raw](https://raw.githubusercontent.com/azet12/KADhosts/master/KADhosts.txt)
The Big List of Hacked Malware Web Sites | [Mitchell Krog](https://github.com/mitchellkrogza) | [Repository](https://github.com//mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/) | [Raw](https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/.dev-tools/_strip_domains/domains.txt)

Your list or repository is not listed here ? Fill a new issue [here](https://github.com/funilrys/funceble/issues/new?title=Please%20add%20my%20list%20or%20repository%20to%20the%20valuable%20links) :smile_cat:

--------------------------------------------------------------------------------

# Special Thanks

Thank you for your awesome `hosts` lists, support or contributions which helped _(and/or still help)_ me build this script. :smile: :+1:

- Adam Warner - [@PromoFaux](https://github.com/PromoFaux)
- Mitchell Krog - [@mitchellkrogza](https://github.com/mitchellkrogz)
- [Pi-Hole](https://github.com/pi-hole/pi-hole)

# Contributors

Thank you for your awesome ideas or contributions which make or made funceble better!! :+1: :100: :1st_place_medal:

- Mitchell Krog - [@mitchellkrogza](https://github.com/mitchellkrogz)

- WaLLy3K - [@WaLLy3K](https://github.com/WaLLy3K)

--------------------------------------------------------------------------------

# `Hosts` files

## What is a hosts file?

A hosts file, named `hosts` (with no file extension), is a plain-text file used by all operating systems to map hostnames to IP addresses.

In most operating systems, the `hosts` file is preferential to `DNS`. Therefore if a domain is resolved by the `hosts` file, the request never leaves your computer.

Having a smart `hosts` file goes a long way towards blocking malware, adware, ransomware, porn and other nuisance websites.

A hosts file like this causes any lookups to any of the listed domains to resolve back to your localhost so it prevents any outgoing connections to the listed domains.

## Recommendations

I'd personally recommend using [Steven's hosts](https://github.com/StevenBlack/hosts) or [Pi-Hole](https://github.com/pi-hole/pi-hole) which are in my opinion the best out there.

--------------------------------------------------------------------------------

# License

```
MIT License

Copyright (c) 2017 Nissar Chababy <contact at funilrys dot com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
