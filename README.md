cBlorb : Resource Packaging for Z-machine and Glulx
=========================================================

---

Blorb is a package format for interactive fiction games. Many such games 
incorporate resources such as sound effects, music, or pictures. Blorb's 
purpose is to bind these together into one file. The format was devised 
by Andrew Plotkin and is used in both the Z-machine and Glulx virtual 
machines, as well as by the Glk library.

cBlorb was written by Graham Nelson for use with [Inform7][].

[Inform7]: http://inform7.com/sources/

This fork includes modifications to make it usable for games written in Inform6.

To build:

    perl inweb/Tangled/inweb.pl -tangle cBlorb
    cc -o cBlorb/Tangled/cBlorb cBlorb/Tangled/cBlorb.c

This is a free, open-source program published under the Artistic License 2.0.


