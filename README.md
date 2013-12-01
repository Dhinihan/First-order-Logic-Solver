First-order-Logic
========================

A program exercice for a logic class at the Instituto de Matemática
e Estatística

Author: Vinícius Nascimento Silva
USP Nº: 7557626

More information at https://github.com/Dhinihan/First-order-Logic-Solver

USAGE
========================

Important: Perl must me installed in your computer.

$ ./FOL FILE [-o|--output = OUTPUT_FILE] [-c|--cnf] [-d|--debbug]

FILE is the path for the input file.

OUTPUT_FILE is the path for the output file.

if the output path is not given, the output is created in the file
'output.txt' or 'output.cnf' if the --cnf option is given.

the option --cnf set the output to the cnf pattern.

the option --debbug shows in the STDIN some informations of the
processing. In this mode, no file is created.
