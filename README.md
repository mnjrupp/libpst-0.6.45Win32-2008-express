libpst-0.6.45Win32-2008-express
===============================

 convert PST (MS Outlook Personal Folders) files to other formats for Outlook 2003 
This version of the readpst was compiled using the PCRE library headers and precompiled dlls.
This library is necessary when using the MS Compiler. They are a wrapper for the POSIX regular 
expression library available in other compilers of the various NIX flavors.
The reason for the precompiled DLLs is not having to compile them myself. You can do as you wish.
The library can be found at: http://sourceforge.net/projects/pcre/
The compiled DLLs are found here http://sourceforge.net/projects/gnuwin32/files/pcre/7.0/pcre-7.0-bin.zip/download.
They are a few versions behind the library source, but it hasn't posed a problem.


Unzip both packages in your favorite download folder. Make sure that you add the include,
and lib directories to your VSC++ directories in  Tools->Options->Project and Solutions->VC++ Directories.
You will need to change the "Additional Include Directories" in the project properties->C/C++->General 
to match the include directories of the PCRE library.
If you get any compile errors, this is where you would need to start.
I have made the necessary changes to the source files, and noted, so as to compile in VC++.
They should still compile in different environments.

