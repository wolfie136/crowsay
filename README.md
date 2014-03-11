crowsay
=======

Tweaks for cowsay and fortune to enable an ASCII Crow T. Robot to recite MST3k quotes.

ASCII Crow T. Robot from saysomethingcryptic.com/text/crow.txt, converted to crow.cow by Chris Andrews, March 2014.

Original quotes file from Bob Corrigan at acknak.blogspot.com/2007/06/resource-fortune-cookie-quote-files.html, modified to remove "catch phrases" and to add further quotes by Chris Andrews, March 2014.

Licence: Fortune file obtained from a blog which displays a CC BY-NC-SA badge. ASCII Crow from a website that was not prominently displaying a licence as of 11/03/2014. Hence overall this project is distributed under CC BY-NC-SA.

Modifiying the quotefile:
=========================

Add new quotes separated by % signs on their own lines. Rebuild the .dat index by running strfile -c % mst3k mst3k.dat in the appropraite directory.

Installation for OS X:
======================

- Install Homebrew (http://www.brew.sh)
- brew install fortune cowsay
- Copy the crow.cow into /usr/local/Cellar/cowsay/<version>/share/cows/
- Copy the mst3k and mst3k.dat files into /usr/local/Cellar/fortune/<version>/share/games/fortunes/
- fortune mst3k | cowsay -f crow 
