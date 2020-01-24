QRAD3 Revision 1.04
===================

MANIFEST

qrad3.exe               Pentium version of executable.
ppro\qbsp3.exe          Pentium Pro version of executable.
qrad3_readme.txt        This file.
qrad3_history.txt       History of all changes made to qrad3.
qrad3_help.txt          Explains changes I have made.
thesun.map              Map with example on how to use Sun features.

====

Revision 1.04

* Seperate Pentium and Pentium Pro executables.
* Added configuration file support.
* Broke up documentation into seperate files.
* Added -radmin parameter.
* Added -savetrace flag.
* Fixed bug that caused problems with _sun when a sky surface
  had a light value smaller than 3.

====

Look at help.txt for info on -radmin.  This has potential of being a major
memory and speed saver.

====

PENTIUM PRO

Included in the ppro folder is a Pentium Pro version of the executable
I compiled with the compiler set to optomize for Pentium Pro processors.
I have not actually been able to test this on a Pentium Pro (my machine
is a simple Pentium of some vintage) so I don't know what actual speed
gains are achieved from using it.

====

gddqrad3 is based off of code that id Software has released to the
public, but NOT into public domain.  Thus, don't try selling this
for money on any CD collection or anything or I may not be the only
one who gets annoyed.

====

                                       == Geoffrey DeWan
                                          gdewan@prairienet.org