
# csvgrep

  Useful for grepping csvs while retaining the header

## Installation

  Install with [ghi](https://github.com/stephenmathieson/ghi)

    $ ghi jb55/csvgrep

  Install with git+make

    $ git clone https://github.com/jb55/csvgrep /tmp/csvgrep && cd /tmp/csvgrep && make install

## Examples

  Grep a csv

    $ csvgrep "Thing" file.csv > newfile.csv

  Retain headers on commands like `ps`

    $ sudo ps laux | csvgrep app - -v

## Usage

    csvgrep <expr> <file> [grep options]

## License

  GPLv2
  
    csvgrep - grep a csv
    Copyright (C) 2015  William Casarin

    This program is free software; you can redistribute it and/or
    modify it under the terms of the GNU General Public License
    as published by the Free Software Foundation; either version 2
    of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc., 51
    Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
