*** Easy CLOG Builder Install for Windows 64 ***

This version is based on sbcl 2.4.3

make.bat and update.bat

1. Unzip where you would like your install to reside
2. Double click make.bat or if wish to upgrade to latest version update.bat
3. builder.exe will be created you can drag to application bar or double click
4. At any time can run update.bat for the latest version, if you change install
   location, you must run make.bat or update.bat

setup.bat

This is used for a fresh brand new install, delete the quicklisp directory and
then run package.bat. If you stored any projects in the quicklisp local projects
you will want to save or move to the common-lisp directory at the root of the
Easy install version.

This will install the latest code from QuickLisp and UltraLisp. If you want a
custom version of any packages place them in common-lisp/
