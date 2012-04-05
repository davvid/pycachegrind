======================================================
pycachegrind: Visualize cProfile data with kcachegrind
======================================================

pycachegrind allows you to run arbitrary Python scripts
using cProfile.  The cProfile data is converted to a form
readable by kcachegrind.

USAGE
=====
Usage: pycachegrind [-o <output_file_path>]
                    (-i <input_file_path> | <scriptfile> [arg]*)

Options:
  -h, --help            show this help message and exit
  -o OUTFILE, --outfile=OUTFILE
                        Save stats to <outfile>
  -i INFILE, --infile=INFILE
                        Read stats from <infile>

SEE ALSO
========
cProfile:
* http://docs.python.org/library/profile.html

kcachegrind:
* http://kcachegrind.sourceforge.net/
