Since Cmder changes ConEmu.xml everytime it opens, its better to move the file
to its own repo.

# Setup

```
cd %USERPROFILE%
git clone git@github.com:fronell/cmder-cfg.git
cd c:\dropbox\apps\cmder\vendor\conemu-maximus5
mklink ConEmu.xml "%USERPROFILE%\cmder-cfg\ConEmu.xml"
mklink ConEmu_startup_tasks.txt "%USERPROFILE%\cmder-cfg\ConEmu_startup_tasks.txt"
```
