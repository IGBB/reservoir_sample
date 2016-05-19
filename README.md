# reservoir_sample
Quickly sample fast[qa] files using the reservoir sample algorithm
<<<<<<< HEAD

## Compile
gcc -lz -o reservoir_sample -Ireadfq reservoir_sample.c

## Usage
Usage: reservoir_sample [OPTION...] FILE ...
Sample fast[aq].gz files using reservoir sampling and output them in fasta
format

  -l, --read_length=LENGTH   Read length to crop to
  -n, --name=NAME            Header name in output
  -s, --reservoir_size=SIZE  Number of reads to output
  -?, --help                 Give this help list
      --usage                Give a short usage message
  -V, --version              Print program version

Mandatory or optional arguments to long options are also mandatory or optional
for any corresponding short options.

Report bugs to <maa146@igbb.msstate.edu>.

=======
>>>>>>> origin
