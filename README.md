# znp
Wrap shell command in ZFS pre/post snapshots

# Installation
Archlinux: znp is available in the AUR
Every other linux distro: copy the shell scripts to a directory in your PATH

# Dependencies
znp uses:
- zfs-utils, more specifically 'zfs snapshot'

# Usage

## create pre snap, run command, create post snap
znp pacman -Syu
znp yum update
znp apt-get upgrade

## List znp snapshots with size and (the first 30chars of) command run
znpc list

# License
This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

A copy of the GNU Affero General Public License version 3 is provided in LICENSE.md. If not, see <https://www.gnu.org/licenses/>. 
