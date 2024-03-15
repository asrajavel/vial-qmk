## Commands:
* qmk flash -c -kb sofle/rev1 -km vial -e CONVERT_TO=kb2040
* qmk compile -c -kb sofle/rev1 -km vial -e CONVERT_TO=kb2040

(run these commands from the root of the vial-qmk directory)

*  When you run flash command - have the keyboard connected, the script will request to press reset at the end.
(on the left side -> lower + top left key, on the right side -> upper + top right key, the lower and uppper buttons are near the large thumb key)
* When you run compile command - it will generate the .uf2 file in the same directory. copy that into the drive of the keyboard. press the same reset combination to enter the drive mode. On copying the uf2 file the drive will automatically close.
