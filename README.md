Solve the following issues:
<br>
Collecting GC information Error in (function (x, col_types) : unused argument (parallel = 1)
<br>
Calls: main ... preprocess.seqz -> sequenza.extract -> gc.sample.stats -> chunk.apply
<br>
Execution halted

The reason:
<br>
The "chunk.apply" function from R iotools package with new version does not have "parallel" parameter which has been changed to "CH.PARALLEL"
