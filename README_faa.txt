rem /Q8 /Q16 or /Q32
rem /x64 or not
rem /mtd /mts mtsd
cd .\VisualMagick\configure
configure.exe /Q8 /x64 /noWizard /mtd
cd ..
VisualDynamicMT.sln
project All x64 Debug  - does have x86 confi
clean solution
build

se visualmagick bin adn lib
