#### Lessons learned:  
  1. (ExtractPlaceValueDigit.bas) When performing floating point math in qbjs the quirkness of the underlying javascript engine may cause precision issues. Using a correction factor by applying an opposite operation to the numbers and pushing the decimal out can possibly correct for this in some cases.
  2. (PrintNumberWithCommas.bas) QBJS function parameters do not need a dim statement it seems the underlying javascript handles this. Javascript function paramaters are passed with no type specified or any checks.
  3. (RandomizeSumAmounts.bas) Learned respect for the work computer scientists do. Tried to work out a sort routine within a for block and did not fully succeed. Will study sorting routines later but for now will still struggle on trying to find obvious methods and compare with correctly established routines.