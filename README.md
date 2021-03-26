
Convert a directory of .wav files to iTunes plus AAC .m4a
---------------------------------------------------------------------
OPTIONS:

convert:
  Actually convert the wav to m4a.

verbose:
  Show the commands that will be run.

play:
  Play the converted files, with minimum play time of 12s. You can override this value with an environment variable called MIN_PLAY_TIME.

check:
  Run some basic sanity checks on the input file (afclip).


Passing no options is the equivalent of 'itunes-convert convert verbose play check'

Options can be negated, as well: 'itunes-convert -check -verbose'

