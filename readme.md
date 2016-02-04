#Cestino Hardware
***


***
##How to Install the Cestino Hardware Package. 
***
Use cd to dive into your_sketchbook_directory/hardware. If there's no hardware directory in your sketchbook, create one and go there. Clone this archive to a directory called cestino with this command:

		$git clone https://github.com/jrstrick/Cestino_Hardware.git cestino

or, if you downloaded the zip archive, rename the folder Cestino_Hardware-master to cestino, and move that to your hardware directory.

 The resulting directory tree should look something like this:

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
