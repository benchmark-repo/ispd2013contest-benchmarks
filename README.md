# Instructions for Creating a Clone of ISPD 2013 Contest Benchmark Set

##	Setting Up a Copy of the Set of ISPD 2013 Contest Benchmarks

### Commands for a UNIX-like Operating System 
- git clone git@github.com:eda-globetrotter/ispd2013contest-benchmarks.git
- git lfs track "*.tgz" "*.gz" "*.sdc" "*.spef" "*.v" "*.tar" "*.bz2"


### Command to Verify the Types of Files Tracked by Git Large File Storage (LFS)
- git lfs track





# Organization of the Repository

+ references.md
	- Contains information for referencing/citing the use of the set
		of ISPD 2013 contest benchmarks.
+ ispd2013
	- cordic benchmark
		* .sdc file
		* .spef file
		* .v file
	- des_perf benchmark
		* .sdc file
		* .spef file
		* .v file
	- edit_dist benchmark
		* .sdc file
		* .spef file
		* .v file
	- fft benchmark
		* .sdc file
		* .spef file
		* .v file
	- lib
		* (Process) technology library, or the cell library (used
			during the technology mapping step of logic synthesis).
	- matrix_mult benchmark
		* .sdc file
		* .spef file
		* .v file
	- parser_helpers
		* parser_helper.cpp
		* parser_helper.h
	- pci_bridge32 benchmark
		* .sdc file
		* .spef file
		* .v file
	- README
		* A text file describing the contents of the directory.
	- simple benchmark
		* .sdc file
		* .spef file
		* .v file
		* .sizes
	- usb_phy benchmark
		* .sdc file
		* .spef file
		* .v file
+ netcard
	- .sdc file
	- .spef file
	- .v file
+ Final
	- cordic_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- cordic_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- des_perf_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- des_perf_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- edit_dist_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- edit_dist_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- fft_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- fft_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- lib
		* (Process) technology library, or the cell library (used
			during the technology mapping step of logic synthesis).
	- matrix_mult_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- matrix_mult_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- netcard_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- netcard_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- parser_helpers
		* parser_helper.cpp
		* parser_helper.h
	- pci_bridge32_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- pci_bridge32_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- usb_phy_fast benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file
	- usb_phy_slow benchmark
		* .sdc file
		* .spef file
		* .v file
		* .runtime file

To test my code thoroughly, sweep through the set of ISPD 2013 contest
	benchmarks in the "./Final" directory, which is obtained by
	uncompressing and unarchiving the file, "ispd2013_final.tar.bz2".

For each benchmark of the ISPD 2013 contest, it contains three files:
- .sdc file
- .spef file
- .v file

In the "./Final" directory, each benchmark also includes a ".runtime"
	file.

In the "./Final" directory, each benchmark is available in two sets of
	files.
	
One set of files belongs to a slower version of the benchmark, which
	can be obtained during logic synthesis (specifically its
	technology mapping step) by selecting slower logic cells/gates.

The other set of files belongs to a faster version of the benchmark,
	which can be obtained during logic synthesis (specifically its
	technology mapping step) by selecting faster logic cells/gates.

The "parser_helpers" subdirectory contains C++ code to help EDA
	software developers develop parsers for the set of ISPD 2013
	contest benchmarks.












