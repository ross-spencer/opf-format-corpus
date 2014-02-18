format-corpus
=============

An openly-licensed corpus of small example files, covering a wide range of formats and creation tools.

All items, apart from the source code under 'tools', is CC0 licenced unless otherwise stated.  The source code is Apache 2.0 Licenced unless otherwise stated.

A recent summary of the contents of the repository can be found [here](http://www.opf-labs.org/format-corpus/tools/coverage/reports/).

##NOTE: This is a remix of the OPF Format Corpus: https://github.com/openplanets/format-corpus
##The purpose of doing this is to allow the format-corpus portion of the repository to be used
##as a corpus for baselining, for enabling re-creation of digital preservation trials and 
##experiments without the pollution of files meant as readmes, indexes or github functionality.

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

## /opf-format-corpus/format-corpus/govdocs1-error-pdfs/

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

## /opf-format-corpus/format-corpus/knowledge-managent/concept-draw/

filename	To Do.cdd
formatName:	ConceptDraw
formatVersion:	?
extensions:	.cdd
mimeType:	
mimeTypeAliases:	
pronomId:	
xmlNameSpace:	
creatorTool:	ConceptDraw
creatorToolUrl:	http://www.conceptdraw.com/
formatSpecUrl:	
comments	Created in 2005 with a trial version of ConceptDraw

## /opf-format-corpus/format-corpus/knowledge-managent/mind-manager/

filename	copac-uknuc.mmp
formatName:	Mind Manager
formatVersion:	2002
extensions:	.mmp
mimeType:	
mimeTypeAliases:	
pronomId:	
xmlNameSpace:	
creatorTool:	Mind Manager
creatorToolUrl:	www.mindjet.com
formatSpecUrl:	
comments	File created originally on a Win95 machine using Mind Manager 2002

filename	copac-uknuc.xml
formatName:	Mind Manager XML (2003)
formatVersion:	
extensions:	.xml
mimeType:	
mimeTypeAliases:	
pronomId:	
xmlNameSpace:	
creatorTool:	Mind Manager
creatorToolUrl:	
formatSpecUrl:	
comments	XML derivative created on a Win XP machine to facilitate migration to NovaMind

filename	copac-uknuc.png
formatName:	Portable Neytwork Graphics
formatVersion:	
extensions:	.png
mimeType:	
mimeTypeAliases:	
pronomId:	
xmlNameSpace:	
creatorTool:	Mind Manager
creatorToolUrl:	
formatSpecUrl:	
comments	Image file created as the XML derivative was made

## /opf-format-corpus/format-corpus/knowledge-managent/nova-mind/

### Curation outline 3.nmind
---
* mimeType: 
* mimeTypeAliases:
* creatorTool: Novamind 4.0
* creatorToolUrl: http://www.novamind.com/

---

This appears to be a single folder with two files, wrapped up as a tar.gz. If you rename and unpack it you get this:

* NovaMind/Contents.xml
  * Plain old XML, no schema.
* NovaMind/fileVersion.txt
  * Contains the text "4.0"
  
### Curation outline 3.opml

---
* mimeType: text/x-opml
* mimeTypeAliases: application/xml, text/xml
* creatorTool: Novamind 4.0
* creatorToolUrl: http://www.novamind.com/

---

Generated from [Curator outline 3.nmind].

## /opf-format-corpus/format-corpus/pcraster/

### About these files
Sample PCRaster (CSF) 2 maps.

### License
All files in this folder: Creative Commons CC0: Public Domain Dedication. See [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/) - To the extent possible under law, Johan van der Knijff has waived all copyright and related or neighboring rights to this work.

## /opf-format-corpus/format-corpus/pdfCabinetOfHorrors/

###The Archivist's PDF Cabinet of Horrors 


#### About these files
Test *PDF* files, created for detecting *PDF* features that are undesired in archival settings. Most of these files were originally created in Microsoft Word 2003, and then converted to *PDF* with Adobe Acrobat Professional 9.5.2. The source Word files are included here as well, but in many cases the *PDFs* required further processing in Acrobat (e.g. embedding videos, attaching files, encryption) so they're probably not that useful.

Exceptions are:

*javascript.pdf*, which was created with Didier Stevens' *make-pdf* tool, which is available here: [http://blog.didierstevens.com/programs/pdf-tools/](http://blog.didierstevens.com/programs/pdf-tools/)

*digitally_signed_3D_Portfolio.pdf*, which was kindly provided by Adobe.

#### Description
Here's a more detailed description of the files (arranged by feature class(es)):

#####Encryption

+ **encryption_openpassword.pdf** - requires password to open the file
+ **encryption_nocopy.pdf** - requires password to copy document contents
+ **encryption_noprinting.pdf** - requires password for printing
+ **encryption_notextaccess.pdf** - requires password to enable text access for screen reader devices for the visually impaired

#####Multimedia
+ **embedded\_video\_avi.pdf** - contains embedded *AVI* movie 
+ **embedded\_video\_quicktime.pdf** - contains embedded *Quicktime* movie

#####Scripts
+ **javascript.pdf** - contains embedded *Javascript*

#####Fonts
+ **text\_only\_fontsNotEmbedded.pdf** - used fonts are not embedded
+ **text\_only\_fontsEmbeddedAll.pdf** - used fonts are embedded
+ **text\_only\_fontsEmbeddedSubset.pdf** - used fonts are embedded as subset
+ **text\_only\_pdfa1b.pdf** - *PDF/A-1a* (with embedded fonts)
+ **test\_fontArialNotEmbedded.pdf** - <del>font *Arial*</del> fonts *Arial* and *Times New Roman*  <del>is</del> are not embedded


#####File attachments
+ **fileAttachment.pdf** - contains a document-level file attachment (an oldskool Quattro Pro spreadsheet, no less!) that is defined using an *EmbeddedFiles* entry in the document’s name dictionary
+ **fileAttachment_fileAttachmentAnnotation.pdf** - contains a page-level file attachment that is defined using a *File Attachment Annotation*

#####External references
+ **externalLink.pdf** - contains link to another document
+ **webCapture.pdf** - uses  Web Capture feature for importing text from a website

#####Byte corruption
+ **corruptionOneByteMissing.pdf** - one byte missing from comment line following file header
 
#####Digitally Signed 3D Portfolio
+ **digitally_signed_3D_Portfolio.pdf** - a PDF 1.7 portfolio with multiple sheets, forms and 3D images; one of the sheets is digitally signed

####License
All files in this folder: Creative Commons CC0: Public Domain Dedication. See [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)

## /opf-format-corpus/format-corpus/statistica/

### About these files
Sample Statsoft Statistica files. Created in Statsoft Statistica for Windows, exact version unknown (might be 4 or 5).  

### License
All files in this folder: Creative Commons CC0: Public Domain Dedication. See [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/) - To the extent possible under law, Johan van der Knijff has waived all copyright and related or neighboring rights to this work.

## /opf-format-corpus/format-corpus/tiff-examples/NANETH_8bpp_grayscale/

---
* formatName: TIFF (Exchangeable Image File Format (Uncompressed), EXIF Uncompressed Image 2.2 (little-endian, EXIF near BOF))
* formatVersion: TIFF 6.0
* extensions: tif, tiff
* mimeType: image/tiff
* mimeTypeAliases: 
* pronomId: x-fmt/387
* xmlNameSpace: 
* creatorTool: Adobe Photoshop CS3 Macintosh
* creatorToolUrl: http://www.adobe.com/support/downloads/detail.jsp?ftpID=3779
* formatSpecUrl: http://partners.adobe.com/public/developer/tiff/

---

####grayscale_8bpp_wrong_bpptag.tif

Invalid 8 bits per sample grayscale baseline TIFF, defined as 16 bits per sample, 
showing malformation when rendered.
Should not validate since it contains several invalid tags, such as "PlanarConfiguration".

ExifTool XML-report included.

Issue:
http://wiki.opf-labs.org/display/SPR/Valid+and+well-formed+TIFF's+with+scanline+corruption
Solution:
http://wiki.opf-labs.org/display/SPR/Solving+TIFF+malformation+using+exiftool

Image courtesy of Dutch digitisation project "Images of the Future":
http://www.beeldenvoordetoekomst.nl/en/
License: CC BY-NC-SA 3.0
http://creativecommons.org/licenses/by-nc-sa/3.0/

## /opf-format-corpus/format-corpus/video/Quicktime/

Apple Quicktime video codecs
============================

These videos are tests of the various, often proprietary, codecs
which ship with Quicktime X. Some of these are supported in open-
source software like ffmpeg, though others (like Apple Intermediate
Codec) are not.

Two formats were omitted, due to difficulties enticing Quicktime to
export the test pattern to them: Apple ProRes 4444, and Apple Pixlet
Video.

Methodology
===========

These videos were created from an ffmpeg test pattern. The command used
to create the original raw video was:

`ffmpeg -f lavfi -i testsrc -c:v rawvideo -c:a none -t 1`

The raw video was then encoded using Quicktime 7. Default settings were
typically used, and "Prepare for Internet Streaming" was disabled. If a
quality setting was available, the highest option was chosen.

All videos are 320x240 at 25fps for one second with no sound, unless the
codec imposed a particular resolution or framerate.

If the codec offered an option of interlaced vs progressive, one video
is provided for each.

License
=======

These were created using ffmpeg's builtin "testsrc" test pattern, which
is presumed to be unlicensed. ffmpeg's code is GPLv2 licensed.

Codec-specific notes
====================

apple-intermediate-codec.mov
----------------------------

A professional video editing codec, intended as an editing format rather
than a delivery format. Not supported by ffmpeg.

XDCAM
-----

The various XDCAM codecs are specific profiles of MPEG-2 used in
professional video. XDCAM HD is an anamorphic format, while
XDCAM EX is a full-resolution HD format. XDCAM HD422 is a
full-resolution format which uses 4:2:2 chroma subsampling instead of
4:2:0.


