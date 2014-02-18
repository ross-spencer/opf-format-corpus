format-corpus
=============

An openly-licensed corpus of small example files, covering a wide range of formats and creation tools.

All items, apart from the source code under 'tools', is CC0 licenced unless otherwise stated.  The source code is Apache 2.0 Licenced unless otherwise stated.

A recent summary of the contents of the repository can be found [here](http://www.opf-labs.org/format-corpus/tools/coverage/reports/).


How to Contribute
=================

See http://wiki.curatecamp.org/index.php/Collecting_format_ID_test_files for more information.

See [metadata-template.ext.md](https://github.com/openplanets/format-corpus/blob/master/metadata-template.ext.md) for a simple per-file metadata template.


Pooled Signatures
=================

As well as pooling example files, we also pool format signatures:

* Tika signatures staged here: https://github.com/openplanets/format-corpus/tree/master/tools/fidget/src/main/resources/tika-bl-staging
* Tika signatures later merged here: [https://github.com/openplanets/format-corpus/blob/master/tools/fidget/src/main/resources/org/apache/tika/mime/custom-mimetypes.xml here]
* DROID signatures go [https://github.com/openplanets/format-corpus/tree/master/tools/fidget/src/main/resources/droid here].

More details here: http://wiki.curatecamp.org/index.php/Improving_format_ID_coverage

=================
=================

# Index

## /opf-format-corpus/format-corpus/ebooks/calibre-0.9.0/

This time, I looked in the app setting and installed the command line tools. This includes 'ebook-convert', which I can then use to generate the varations.

## /opf-format-corpus/format-corpus/file-archive/

### About this folder
This folder contains example files for a variety of file archive formats (i.e. container/compression formats such as the ones listed here: [http://en.wikipedia.org/wiki/List_of_archive_formats](http://en.wikipedia.org/wiki/List_of_archive_formats). 

## /opf-format-corpus/format-corpus/file-archive/arj/

---
* formatName: ARJ (**A**rchived by **R**obert **J**ung) archive 
* formatVersion: unknown
* extensions: .arj
* mimeType: N/A
* mimeTypeAliases: N/A 
* pronomId: N/A 
* xmlNameSpace: N/A 
* creatorTool: ARJ.exe, exact version unknown (file was created some time around 1997/98)
* creatorToolUrl: N/A 
* formatSpecUrl: N/A

---

### License
All files in this folder: Creative Commons CC0: Public Domain Dedication. See [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/) - To the extent possible under law, Johan van der Knijff has waived all copyright and related or neighboring rights to this work.

## /opf-format-corpus/format-corpus/filesys-trials/

A home for mostly empty files.  The idea is to collect the files, file paths and names that tend to break tools. There's an empty file, GitHub doesn't support the empty dir. I'll be structuring as I go, the names and folder structures should be descriptive, but feel free to add your own collections sub-collections.
 
If a particular file name or path upsets a piece of software, put an example here. The current homes are:

a-bad-name
----------

Bad file names and extensions, NOT paths go here.  The place for character-set issues, wierd characters, unconventional use of period, long names, short names, you get the idea....


a-bad-path
----------

Like the name says, a home for all path related issues.  Long paths, silly characters, and so on.  There may be some issues with GitHub accepting certain names and paths but we'll see.

## /opf-format-corpis/format-corpus/govdocs1-error-pdfs/

### PDF files from Govdocs1 that may cause errors

#### About these files
Test *PDF* files from Govdocs1.  About 130,000 PDF files (all PDFs from the first ~500k files in Govdocs) were tested against PDF software and these are the files that caused problems.  They may well be broken but they may be useful for stress-testing.

#### Description
+ **error_set_1** contains pdf files that failed in a particular way
+ **error_set_2** contains pdf files that failed in a different way

#### License
All PDF files in this folder and subfolders are copied from Govdocs1;

More information about these files can be found at [http://digitalcorpora.org/corpora/files]

##### Relevant quotes:

> We have created and released a corpus of 1 million documents that are freely available for 
> research and may be (to the best of our knowledge) freely redistributed. These documents were 
> obtained by performing searches for words randomly chosen from the Unix dictionary, numbers 
> randomly chosen between 1 and 1 million, and randomized combinations of the two, for documents 
> of specified file types that resided on web servers in the .gov domain using the Yahoo an 
> Google search engines.

> If you decide to use this corpus in published research, the appropriate citation is: Garfinkel, 
> Farrell, Roussev and Dinolt, Bringing Science to Digital Forensics with Standardized Forensic 
> Corpora, DFRWS 2009, Montreal, Canada

## /opf-format-corpus/format-corpus/jp2k-formats/

### Contents of this folder

This folder contains sample images for each of the *JPEG 2000* file formats:

+ [*balloon.jp2*][sampleJP2] - [JPEG 2000 Part 1][JP2] (JP2) image, created using [Aware JPEG 2000 SDK][Aware] <sup>*</sup>

+ [*balloon.jpf*][sampleJPX] - [JPEG 2000 Part 2][JPX] (JPX) image, created using [Kakadu][Kakadu] 6.4 *

+ [*balloon.jpm*][sampleJPM] - [JPEG 2000 Part 6][JPM] (JPM) image, created using [Luratech JPEG 2000 plugin][Luratech] for [IrfanView][IrfanView] <sup>*</sup>

+ [*balloon.j2c*][sampleJ2C] - JPEG 2000 Codestream, created using [Kakadu][Kakadu] 7.1 *

+ [*Speedway.mj2*][sampleMJ2] - [JPEG 2000 Part 3][MJ2] (MJ2) video (aka "motion JPEG 2000"), created using [OpenJPEG][OpenJPEG] <sup>\#</sup>

Note that the standard file extension of *JPX* files is `.jpf` (section M.2.1 of the [specification][JPX]):

> When stored in traditional computer file systems, JPX files
> should be given the file extension ".jpf" (readers should allow mixed case).

Stand-alone *JPEG 2000* codestreams are pretty rare (they're usually embedded within the other formats), but they do exist. File extensions vary, but `.j2c` is often used.
  

###Image attribution

<sup>*</sup>Created from the following source image: 


[http://commons.wikimedia.org/wiki/File:1783_balloonj.jpg](http://commons.wikimedia.org/wiki/File:1783_balloonj.jpg "http://commons.wikimedia.org/wiki/File:1783_balloonj.jpg")

> 1786 description of the historic Montgolfier Brothers' 1783 balloon flight. Illustration with engineering proportions and description.

Public Domain.

<sup>#</sup>Source: 
[http://www.openjpeg.org/samples/Speedway.mj2](http://www.openjpeg.org/samples/Speedway.mj2 "http://www.openjpeg.org/samples/Speedway.mj2")


[JP2]:http://www.jpeg.org/public/15444-1annexi.pdf
[JPX]:http://www.jpeg.org/public/15444-2annexm.pdf
[JPM]:http://www.jpeg.org/public/fcd15444-6.pdf
[MJ2]:http://www.jpeg.org/public/fcd15444-3.pdf

[Aware]:http://www.aware.com/imaging/jpeg2000sdk.html
[Kakadu]:http://www.kakadusoftware.com/
[Luratech]:https://www.luratech.com/en/products/imaging-solutions/additional-imaging-solutions.html
[IrfanView]:http://www.irfanview.com/
[OpenJPEG]:http://www.openjpeg.org/



[sampleJP2]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jp2
[sampleJPX]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jpf
[sampleJPM]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jpm
[sampleJ2C]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.j2c
[sampleMJ2]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/Speedway.mj2
[sampleImages]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/
[magic]:https://github.com/bitsgalore/jp2kMagic/tree/master/magic/

[magicUncompiled]:https://github.com/bitsgalore/jp2kMagic/tree/master/magic/jpeg2000Magic
[magicCompiled]:https://github.com/bitsgalore/jp2kMagic/tree/master/magic/jpeg2000Magic.mgc

## /opf-format-corpus/format-corpus/jp2k-test/

### Contents
This folder contains a small test corpus of *JPEG 2000* (Part 1 and Part 2) images. 

All images were compressed lossily at a ratio of about 45:1. Encoding options (tile size, progression order, etc.) are not uniform across all samples, and in most cases the application defaults were used (except for the *Aware*-created images). The images are subdivided into 3 groups:

+ *Resolution* - shows handling of resolution fields by different encoders
+ *icc* -  shows handling of ICC profiles by different encoders (as well as some *Photoshop*-specific weirdness)
+ *byteCorruption* - shows effects of removal/modification of bytes after image creation (these files were deliberately butchered - no encoder faults to blame!)  

[*Jpylyzer*][jpylyzer] output files are *NOT* included for each image (note that these are best viewed in an *XML* editor as they are not pretty-printed). 
 
The table below gives a description of the dataset:


<table border=1 cellspacing=0 cellpadding=10 width=841
>

<td width=841  colspan=4 valign=bottom >
<br/><b>Part 1: Resolution</b>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/><i>File</i>
</td>
<td width=73  valign=bottom >
<br/><i>Format</i>
</td>
<td width=270  valign=bottom >
<br/><i>Creator
application</i>
</td>
<td width=255  valign=bottom >
<br/><i>Remarks</i>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon.tif
</td>
<td width=73  valign=bottom >
<br/>TIFF
</td>
<td width=270  valign=bottom >
<br/>IrfanView, resolution fields added using ExifTool 
</td>
<td width=255  valign=bottom >
<br/>Source
image
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_aware.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>Aware
JPEG 2000 SDK 3.19.2.2
</td>
<td width=255  valign=bottom >
<br/>Resolution
in "Capture Resolution" box
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_oj.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>OpenJPEG 1.5, image_to_j2k tool
</td>
<td width=255  valign=bottom >
<br/>No
resolution box
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_gm.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>GraphicsMagick 1.3.16, convert tool (uses JasPer 1.9.0)
</td>
<td width=255  valign=bottom >
<br/>No
resolution box
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_kdu61.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>Kakadu 6.1, kdu_compress tool
</td>
<td width=255  valign=bottom >
<br/>Resolution
in "Display Resolution" box
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_kdu71.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>Kakadu 7.1, kdu_compress tool
</td>
<td width=255  valign=bottom >
<br/>Resolution
in "Capture Resolution" box
</td>
</tr>
<tr >
<td width=841  colspan=4 valign=bottom >
<br/><b>Part 2: ICC profiles + Photoshop weirdness</b>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/><i>File</i>
</td>
<td width=73  valign=bottom >
<br/><i>Format</i>
</td>
<td width=270  valign=bottom >
<br/><i>Creator
application</i>
</td>
<td width=255  valign=bottom >
<br/><i>Remarks</i>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_eciRGBv2.tif
</td>
<td width=73  valign=bottom >
<br/>TIFF
</td>
<td width=270  valign=bottom >
<br/>Adobe
Photoshop CS4
</td>
<td width=255  valign=bottom >
<br/>Source
image, contains embedded ICC profile
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_eciRGBv2_aware.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>Aware
JPEG 2000 SDK 3.19.2.2
</td>
<td width=255  valign=bottom >
<br/>Contains
ICC profile, embedded using "Restricted ICC" method
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_eciRGBv2_ps_
<br/>adobeplugin.jpf
</td>
<td width=73  valign=bottom >
<br/>JPX
</td>
<td width=270  valign=bottom >
<br/>Adobe
Photoshop CS4 + Adobe JPEG2000 plugin 2.0
</td>
<td width=255  valign=bottom >
<br/>Wrong
'brand' field; ICC profile embedded using "Any ICC" method
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_eciRGBv2_ps_
<br/>adobeplugin_jp2compatible.jpf
</td>
<td width=73  valign=bottom >
<br/>JPX
</td>
<td width=270  valign=bottom >
<br/>Adobe
Photoshop CS4 + Adobe JPEG2000 plugin 2.0
</td>
<td width=255  valign=bottom >
<br/>Wrong 'brand'
field; contains two versions of ICC profile: one embedded using "Any
ICC" method; other embedded using "Restricted ICC" method,
with description ("Modified eciRGB v2")
and profileClass ("Input Device") changed
relative to original profile.
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_eciRGBv2_ps_
<br/>kduplugin.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>Adobe
Photoshop CS4 + j2k plugin 2.01 (based on Kakadu)
</td>
<td width=255  valign=bottom >
<br/>Contains
ICC profile, embedded using "Restricted ICC" method; profileClass changed relative to original profile
("Input Device")
</td>
</tr>
<tr >
<td width=841  colspan=4 valign=bottom >
<br/><b>Part 3: Byte corruption</b>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/><i>File</i>
</td>
<td width=73  valign=bottom >
<br/><i>Format</i>
</td>
<td width=270  valign=bottom >
<br/><i>Creator
application</i>
</td>
<td width=255  valign=bottom >
<br/><i>Remarks</i>
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon.jpg
</td>
<td width=73  valign=bottom >
<br/>JPEG
</td>
<td width=270  valign=bottom >
<br/>
</td>
<td width=255  valign=bottom >
<br/>Source image
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_intact.jp2
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>
</td>
<td width=255  valign=bottom >
<br/>Intact image (reference)
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_trunc1.jp2*
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>
</td>
<td width=255  valign=bottom >
<br/>Last byte
missing*
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_trunc2.jp2*
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>
</td>
<td width=255  valign=bottom >
<br/>Truncated
at byte 5000*
</td>
</tr>
<tr >
<td width=243  valign=bottom >
<br/>balloon_trunc3.jp2*
</td>
<td width=73  valign=bottom >
<br/>JP2
</td>
<td width=270  valign=bottom >
<br/>
</td>
<td width=255  valign=bottom >
<br/>Missing
data in most of last tile-part*
</td>
</tr>

<tr >
<td width=841  colspan=4 valign=bottom >
<br/>* Image
was manually edited (bytes were removed) after creation to demonstrate
effects of truncation -image faults are purely artificial and NOT related to
the creator application!!!!!
</td>
</tr>
</table>


###Image attribution and provenance

All images are derived from the following source image: 

[http://commons.wikimedia.org/wiki/File:1783_balloonj.jpg](http://commons.wikimedia.org/wiki/File:1783_balloonj.jpg "http://upload.wikimedia.org/wikipedia/commons/a/a8/1783_balloonj.jpg")

> 1786 description of the historic Montgolfier Brothers' 1783 balloon flight. Illustration with engineering proportions and description.

Public Domain.

Resolution fields and ICC profile were added specifically to demonstrate how these features are handled by different encoders. The diagram below shows the approximate workflow:

![](https://raw.github.com/openplanets/format-corpus/master/jp2k-test/diagram.png)


[jpylyzer]: http://www.openplanetsfoundation.org/software/jpylyzer
[Aware]:http://www.aware.com/imaging/jpeg2000sdk.html
[Kakadu]:http://www.kakadusoftware.com/
[Luratech]:https://www.luratech.com/en/products/imaging-solutions/additional-imaging-solutions.html
[IrfanView]:http://www.irfanview.com/
[OpenJPEG]:http://www.openjpeg.org/
[GraphicMagick]:http://www.graphicsmagick.org/


[sampleJP2]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jp2
[sampleJPX]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jpf
[sampleJPM]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.jpm
[sampleJ2C]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/balloon.j2c
[sampleMJ2]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/Speedway.mj2
[sampleImages]:https://github.com/bitsgalore/jp2kMagic/tree/master/sampleImages/
[magic]:https://github.com/bitsgalore/jp2kMagic/tree/master/magic/
