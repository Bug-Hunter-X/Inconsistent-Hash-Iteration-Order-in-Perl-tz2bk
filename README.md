This repository demonstrates an uncommon Perl bug related to the inconsistent iteration order of hashes. The bug.pl file shows code that iterates through a hash, but the output order may vary between runs. The bugSolution.pl file provides a workaround using `sort` to ensure consistent output.