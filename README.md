Panoptic v0.1
===

Scan systems for default file locations

### Help Menu
    --target              set the target to test.
    --param               set the parameter to test.
    --os                  set a specific operating system to limit searches.
    --software            set the name of the software to search for.
    --category            set a specific category of software to look for.
    --type                set the type of file to search for (conf or log).
    --help                print this menu.

### Examples
    ./panoptic.py --help
    ./panoptic.py --target "http://localhost/lfi.php?file=test.txt" --param "file"
