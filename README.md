# assignment-1-yes
Recreate Unix `yes` in C

1. By default print 'y' infinitely to standard output.
2. Optionally print some other string specified as command-line arguments.
3. Respond to the --help & --version command line arguments.


## Part Two

Come closer to GNU's yes in terms of performance.

      yes | pv > /dev/null
      26GB 0:00:12 [ 110MB/s] [ <=> ]

Your PDF should include an analysis of throughput rates of GNU's yes compared with your original version, and any new versions you create (similar to Table 13-1 of TLPI).
