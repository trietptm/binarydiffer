# Quick Start #
  1. Copy BinaryDiffer.plw to IDA plugins directory
  1. Start BinaryDiffer.exe
  1. Start up two IDA sessions and open binaries to diff to each IDA session
  1. Initiate BinaryDiffer plugin in each IDA session(Edit -> Plugins -> ”Binary Differ”)
  1. When the analysis is done, you can see "Matched Functions" tabs.
  1. If you click the matches to analyze, it will show graph view of the function.
  1. It has node colors painted
|Color|Meaning|
|:----|:------|
|green|It has match in the other binary|
|yellow|It has match in the other binary, but the node has difference|
|red  |The node is severely modified|
|white|It doesn't have match in the other binary|