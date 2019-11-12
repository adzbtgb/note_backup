# note_backup



rem


set SourcePath=.
rd /s/q %SourcePath%\Debug
rd /s/q %SourcePath%\*.tlog
rd /s/q %SourcePath%\temp
rem  rd /s/q %SourcePath%\ipch
for /r %%i in (ipch) do rd /s /q "%%i"
rem del /s/q %SourcePath%\*.exe
del /s/q %SourcePath%\*.obj 
del /s/q %SourcePath%\*.opt
del /s/q %SourcePath%\*.ncb
del /s/q %SourcePath%\*.aps
del /s/q %SourcePath%\*.tlh
del /s/q %SourcePath%\*.tli
del /s/q %SourcePath%\*.pch
del /s/q %SourcePath%\*.pdb
del /s/q %SourcePath%\*.sbr
del /s/q %SourcePath%\*.idb
del /s/q %SourcePath%\*.bsc
del /s/q %SourcePath%\*.exp
del /s/q %SourcePath%\*.ilk
del /s/q %SourcePath%\*.sdf
del /s/q %SourcePath%\*.tlog
del /s/q %SourcePath%\*.i
del /s/q %SourcePath%\*.vshost.exe
