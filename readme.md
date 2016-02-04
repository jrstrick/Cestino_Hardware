#Cestino Hardware
***


***
##How to Install the Cestino Hardware Package. 
***
Use cd to dive into your_sketchbook_directory/hardware. Drop the cestino folder from the archive there. The resulting directory tree should look something like this:
		your_sketchbook_directory_name/hardware
		└── cestino
		    ├── avr
		    │   ├── boards.txt
		    │   ├── boards.txt~
		    │   ├── boot.h
		    │   ├── bootloaders
          │	  │   └── optiboot
		    │   ├── libraries
		    │   ├── mkfile-not-used
		    │   ├── oldboards.txt
		    │   ├── pin_defs.h
		    │   ├── platform.txt
		    │   ├── README.md
		    │   ├── stk500.h
		    │   ├── unused-cores
		    │   ├── variants
		    │   └── Wire
		    └── readme.md
Arduino should do the rest.
***
##Build Instructions
***

Use cd to get into the bootloaders/optiboot directory, here:
		your_sketchbook_directory_name/hardware
		└── cestino
		    └── avr
		        ├── boards.txt
		        ├── boards.txt~
		        ├── boot.h
		        └── bootloaders
           	      └── optiboot <-- here

and type:
		$make cestino1284p
It should just work.
