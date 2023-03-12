# ZXSpectrum
Dumping ground for my original 1980s ZX Spectrum code.

I think the 'psioed' font editor could be the 'Character Generator' in the Psion Horizons cassette. Written in BASIC. Not by me! There's a sugegstion this could be an adapted version of the one on the Horizons tape, allowing more characters to be edited, so I'll keep it here for now in case it's of wider interest.

'htv-logo' and 'c4-logo' are BASIC programs for drawing TV company logos.

VSavon and Holly Tree are imaginary TV company logos, the former looks like it was coded by Mark Owen, I think the latter by Bruce Guthrie. It looks like Mark's VSavon code also reprograms a character to be the Avonside logo once you run it - compare the REM in line 125 before and after you run it!

'Oinvaders' (Zappovaders?) is a space invaders type game written by Mark Owen in BASIC with a machine code element 'MC1' which gets loaded - hence the WAV file rather than .tap - this seems to load ok in FUSE.

'inline' is a Broadway-like font, not sure if I created that or not. This loads ok using typeface-loader or loading it in location 31231 and doing POKE 23607,121 

'inline-2' is the same font shifted 1 byte later so it loads ok by dragging and dropping onto screenshots such as https://damieng.com/typography/zx-origins/homestead/

