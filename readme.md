# Dogecoin Paper Wallet

*This is a fork of  wellsriley's [dogecoinpaperwallet](https://github.com/wellsriley/dogecoinpaperwallet), which a fork of nsfmc's [paperwallet](https://github.com/nsfmc/paperwallet), which is a fork of cantonbecker's [bitcoinpaperwallet](https://github.com/cantonbecker/bitcoinpaperwallet) JavaScript powered offline bitcoin address generator. Please forgive the lack of Dogespeak in this README – this stuff is important.*
This for is for the awesome 100 doge bill art by [/u/trevorinfidel](http://www.reddit.com/user/trevorinfidel).

--------------------------------------

#### The original bitcoinpaperwallet.com README:

### bitcoinpaperwallet.com

This project is a fork of bitaddress.org, the original trustworthy
JavaScript powered offline bitcoin address generator.

This attractive paper wallet design is two-sided and folds up to
hide the private key. Optional tamper-evident hologram tape can be purchased
to provide extra security against snooping. This generator is ONLY
for generating secure paper wallets, either using Javascript-based cryptography
or by supplying keys you have generated using your own means (vanitygen, dice.)

Use bitaddress.org if you need BIP38, brain wallets, or bulk addresses.


### HOW TO USE THIS GENERATOR

1) Extract the ZIP file
2) Open up the 'index.html' file with your web browser.
3) Follow the steps for calibrating your printer and then printing
   the front and back of each wallet. Use landscape mode when printing!

Rendering and printing seems to work best using:

   OS X:     Safari or Chrome or Firefox
   Windows:  Chrome or Firefox
   Linux:    Firefox


### COMPARED WITH BITADDRESS.ORG

Images and resources have been moved out of the .html file (where they were
base-64 encoded) and into an images directory to make the code easier to review.

All cryptographic functions are verifiably identical to those in bitaddress.org.
(Run a "diff" between this project and bitaddress.org if you want to be sure.)

You can also bypass the random key generator and supply your own keys or so-called
"vanity addresses".


### HOW TO VERIFY THE AUTHENTICITY OF THIS DOWNLOAD

After downloading the ZIP package for this generator, you should find a file
named index.html.sig which you can use to:

* Verify that index.html hasn't been tampered with, and
* Get proof that it really was authored by Canton Becker (canton@gmail.com)
  whose GPG public key and fingerprint should be confirmed at http://cantonbecker.com

For example, if you have GPG installed, you should be able cd to the appropriate
directory and type in these two commands:

  gpg --recv-key 36E1D9B6
  gpg --verify --with-fingerprint index.html.sig index.html

And then verify the resulting signature's fingerprint against Canton Becker's
published fingerprint at http://cantonbecker.com

If you get warnings like "This key is not certified, there is no indication that
the key belongs to the owner" do not worry, this is normal.

- Canton Becker
http://cantonbecker.com
canton@gmail.com



----------------------------------------------------------
--- The original bitaddress.org README continues below ---
----------------------------------------------------------

Now Bitcoin addresses and their corresponding private key can be conveniently
generated in a web browser.

The bitaddress.org project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the
JavaScript locally and trust that the JavaScript did not change after being
loaded.

Here is a link to the BitcoinTalk.org forum topic discussing this project:
https://bitcointalk.org/index.php?topic=43496.0


Please send DONATIONS for this project to Bitcoin Address:
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN


END USER NOTES:
 1) To print QRCode in IE8 you must enable the "Print Background Colors and
    Images" checkbox on the "Page Setup" screen.
 2) For Bulk Wallet I recommended using Google Chrome, it's the fastest.
 3) Requires IE8+, Firefox, Chrome or sufficient JavaScript support.
 4) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.
 5) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.
 6) Art Wallet does not work properly in IE8 due to CSS limitations.


Notice of Copyrights and Licenses:
---------------------------------------
The bitaddress.org project, software and embedded resources are copyright bitaddress.org.
The bitaddress.org name and logo are not part of the open source license.

Portions of the all-in-one HTML document contain JavaScript codes that are the copyrights
of others. The individual copyrights are included throughout the document along with their
licenses. Included JavaScript libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:
JavaScript function   License
-------------------   --------------
Array.prototype.map   Public Domain
window.Crypto     BSD License
window.SecureRandom   BSD License
window.EllipticCurve    BSD License
window.BigInteger   BSD License
window.QRCode     MIT License
window.Bitcoin      MIT License

The bitaddress.org software is available under The MIT License (MIT)
Copyright (c) 2011-2012 bitaddress.org

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be included in all copies
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
