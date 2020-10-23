# Ultimate Chordbook
This is a LaTeX package which extends the excelent package `songs` in order to resemble the pdf output of tabs from ulitmate-guitar.com. Check the PDF in this repo how it looks!

## How to use this for your own chordbook
Copy `ultimatechordbook.sty` to a LaTeX project and put `\usepackage{ultimatechordbook}` in your preable. That's it!

I recommend using the example structure like I have in this repo.

For easy conversion, use the website https://ultimate.ftes.de/ for converting Ultimate Guitar Tabs to LaTeX.

## Custom stuff
- Themed like Ultimate Guitar pdfs
- Extra options for `songs`' `\beginsong`:
	- `key`: the key the song is in
	- `tun`: tuning of the guitar
- New page after every song

## TODO
- Remove workaround that atleast one 0 finger is required for chord alignment without fingers
- Option to keep `\sbarheight` with newpages between songs.
- Index generation?

## Attribution
Music and words by Jonathan Coulton and fall under the Creative Commons Attribution-Noncommercial 3.0 Unported license.

## Licence
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
