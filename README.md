# KDSNP
Program:        KDE
Description:    A toolkit for kernel-based approach to detecting high-order genetic epistasis
Author:         Kento Kodama, Hiroto Saigo
Contact:        saigo@bio.kyutech.ac.jp
Year:           2015     
LICENSE:        Released under GNU General Public License, v2
Documentation:  http://saigo-www.bio.kyutech.ac.jp/kde
Compilation:    To help compiling, see documentation (basically, just be sure to select the 
                correct Makefile and type make -f Makefile.*)
Usage:          Type "kde" or "./kde" from the command line followed by the options of choice (see documantation)
Example:        Two example files test1.phe and test.gen are included in the distribution;
                for example, once KDE is installed try running:

                kde --gen test.gen --phe test.phe 

                kde --gen test.gen --phe test.phe --out test.result

                kde --gen test.gen --phe test.phe --degree 5

                kde --gen test.gen --phe test.phe --fold 5

                etc...
