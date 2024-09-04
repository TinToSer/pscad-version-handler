# pscad-version-handler
Gives option to set which PSCAD version to open by-default and which on demand, just right click any PSCAD file and you will see the second option as "Open PSCAD" and then select the version to open with

## For setting which pscad version will open by default change in 'setting.reg'

### For making PSCAD 4.x as default
```
;           For defining which version of PSCAD will be opened by-default or on rightclick
[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PSCAD.EMTDC.x4\Shell\Open\Command]
@="C:\\Program Files (x86)\\PSCAD46\\bin\\win64\\pscad.exe DCLK \"%1\""
[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PSCAD.EMTDC\Shell\Open\Command]
@="C:\\Program Files (x86)\\PSCAD46\\bin\\win64\\pscad.exe DCLK \"%1\""

;======================================END====================================================
```
### For making PSCAD 5.x as default
```
;           For defining which version of PSCAD will be opened by-default or on rightclick
[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PSCAD.EMTDC.x4\Shell\Open\Command]
@="C:\\Program Files (x86)\\PSCAD50\\bin\\win64\\pscad.exe DCLK \"%1\""
[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PSCAD.EMTDC\Shell\Open\Command]
@="C:\\Program Files (x86)\\PSCAD50\\bin\\win64\\pscad.exe DCLK \"%1\""

;======================================END====================================================
```

## Steps:- 
  - Double click the 'setting.reg' file
  - No second step :)


Help has been given inside .reg file itself, no rocket science, very easy to edit

========Thanks and once again I will say that if you face any inconvenience then remember God in mind and me in Person ==========
