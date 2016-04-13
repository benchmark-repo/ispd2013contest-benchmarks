# Instructions for Creating a Clone of ISPD 2013 Contest Benchmark Set

##	Setting Up a Copy of the Set of ISPD 2013 Contest Benchmarks

### Commands for a UNIX-like Operating System 
- git clone git@github.com:benchmark-repo/ispd2013contest-benchmarks.git
- git lfs track "*.tgz" "*.gz" "*.sdc" "*.spef" "*.v" "*.tar" "*.bz2"

See \cite{Olson2016} regarding using the software utility *Git Large File Storage (LFS)* to manage large files (for the benchmarks) in the benchmark repository. 

### Command to Verify the Types of Files Tracked by Git Large File Storage (LFS)
- git lfs track





# Organization of the Repository

+ references.md
	- Contains information for referencing/citing the use of the set
		of ISPD 2013 contest benchmarks.
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
- .runtime file

Each benchmark is available in two sets of files.
	
One set of files belongs to a slower version of the benchmark, which
	can be obtained during logic synthesis (specifically its
	technology mapping step) by selecting slower logic cells/gates.

The other set of files belongs to a faster version of the benchmark,
	which can be obtained during logic synthesis (specifically its
	technology mapping step) by selecting faster logic cells/gates.

The "parser_helpers" subdirectory contains C++ code to help EDA
	software developers develop parsers for the set of ISPD 2013
	contest benchmarks.












#	Author Information

The MIT License (MIT)

Copyright (c) <2016> <Zhiyang Ong>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d [:cntrl:] | tr -d 'ir' | tr y "\n"		Don't compromise my computing accounts. You have been warned.

