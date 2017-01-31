# iText is a Java PDF library originally dual licensed under MPL/LGPL #

## Background ##

Beginning with version 5.0 the developers have moved to the AGPL to improve their ability to sell commercial licenses. I fully respect the developers' wishes and rights. To assist those desiring to stick with the old license I'm making the final MPL/LGPL version more easily available.

## Contributing ##
This is a static mirror!
iText has moved on to its new license, and it's not my intention to continue to develop this repo as a fork.
If you'd like to contribute to iText, that's awesome! I encourage you to!

Here are some options:
- If you are okay with the AGPL, send your contributions [upstream](http://itextpdf.com/).
- A fork of this project with a LGPL/MPL license is actively maintained and developed here:  This is actively maintained and improved here: https://github.com/librePDF/OpenPDF/

Good luck!

## [Javadocs](http://ymasory.github.com/iText-4.2.0/) ##

## Download ##

I have compiled the project using Java 6. The jars are available under the [Downloads tab](https://github.com/ymasory/iText-4.2.0/downloads).

## Compile ##

Since iText 4.2.0 is compatible with JDK 4+, you may wish to recompile yourself to get JDK 4/5 compatiblity.
To do so:

```sh
cd iText-4.2.0/src
ant jar
ant jar.rups
ant jar.rtf
```

## Maintaining binary compatability with iText 5+ ##

Additionally, version 5.0 breaks binary compatibility by changing package names from ``com.lowagie`` to ``com.itextpdf``.
To offer compatibility with compatibly-licensed code targeting 5.0, I've also produced a jar of 4.2.0 using ``com.itextpdf``.
See the [Downloads tab](https://github.com/ymasory/iText-4.2.0/downloads).
You can find the source in the [``com.itextpdf``](https://github.com/ymasory/iText-4.2.0/tree/com.itextpdf) branch of the repository.
You can compile with the instructions above.
