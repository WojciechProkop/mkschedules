# mkschedules
The Perl script will read comma-separated value (CSV) data describing scheduled courses. Given this input, the script will
normally generate LATEX to standard output for typesetting room schedules. Commandline arguments may augment its behaviour

./mkschedulesgood, for generating room schedules

usage: ./mkschedulesgood [options] [csv file]

Options:
  -h        display help and terminate
  -s        display statistics and terminate
  -o script  output bash 'SCRIPTNAME' for splitting the PDF
