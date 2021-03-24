# bat

## To Autorun these macros which add aliases for unix commands, execute:

**reg add "HKCU\Software\Microsoft\Command Processor" /v Autorun /d "doskey /macrofile=\"c:\bat\macros.doskey\"" /f**

## To verify the key is added, execute:

**reg query "HKCU\Software\Microsoft\Command Processor" /v Autorun**
