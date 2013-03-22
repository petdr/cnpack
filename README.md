cnpack
======

CNPack helpers for Delphi IDE

This is a clone of the subversion repository located at https://code.google.com/p/cnpack/source/checkout

debug
=====

1. Open project
2. Select project options
3. Goto Linking
4. Ensure that "Include Remote Debug Symbols" is set to true.
5. Goto Menu Run/Parameters...
6. Set host application to C:\Program Files (x86)\Embarcadero\RAD Studio\9.0\bin\bds.exe
7. Edit registry so that [HKEY_CURRENT_USER\Software\Embarcadero\BDS\9.0\Experts] points to the newly created dll
8. Press F9 to run applicatoin
9. After exiting don't forget to set back the registry to point to the installed cnpack
