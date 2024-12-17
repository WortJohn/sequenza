Solve the following issues:
-
Collecting GC information Error in (function (x, col_types) : unused argument (parallel = 1)
Calls: main ... preprocess.seqz -> sequenza.extract -> gc.sample.stats -> chunk.apply
Execution halted

The reason:
-
The "chunk.apply" function from R iotools package with new version does not have "parallel" parameter which has been changed to "CH.PARALLEL"
