## MS08-021 ##

| | **Filename**| **Version** |
|:|:------------|:------------|
| pre | gdi32.dll   | 5.1.2600.3159 on WinXP sp2 |
| post | gdi32.dll   | 5.1.2600.3316 on WinXP sp2 |


### Overall tab pages in IDA to show diffing results ###
![http://lh6.google.com/sunghun.hyun/R_xO3SR4seI/AAAAAAAAACM/WiJr-LrZcDk/s800/ms08_021.jpg](http://lh6.google.com/sunghun.hyun/R_xO3SR4seI/AAAAAAAAACM/WiJr-LrZcDk/s800/ms08_021.jpg)

### Integer overflow occured when calling RtlAllocateHeap() ###
![![](http://lh4.google.com/sunghun.hyun/R_xO2yR4sdI/AAAAAAAAACE/RIeVND-t-nM/s800/ms08_021_gdi_intoverflow_to_heapoverflow.jpg)](http://lh4.google.com/sunghun.hyun/R_xO2yR4sdI/AAAAAAAAACE/RIeVND-t-nM/s800/ms08_021_gdi_intoverflow_to_heapoverflow.jpg)

### Integer underflow ###
![http://lh6.google.com/sunghun.hyun/R_xO2SR4scI/AAAAAAAAAB8/ZXcnNym-oag/s800/ms08_021_gdi_intunderflow_to_stackoverflow.jpg](http://lh6.google.com/sunghun.hyun/R_xO2SR4scI/AAAAAAAAAB8/ZXcnNym-oag/s800/ms08_021_gdi_intunderflow_to_stackoverflow.jpg)

### showing how well binarydiffer catches the patched function that added arguments ###
![http://lh3.google.com/sunghun.hyun/R_xO1iR4sbI/AAAAAAAAAB0/h3VBXumCDYs/s800/ms08_021_gdi_argChanged.jpg](http://lh3.google.com/sunghun.hyun/R_xO1iR4sbI/AAAAAAAAAB0/h3VBXumCDYs/s800/ms08_021_gdi_argChanged.jpg)

### simple patch from wcscpy to safe string copy function ###
![http://lh5.google.com/sunghun.hyun/R_xO1CR4saI/AAAAAAAAABo/ejz3kOul6Qg/s800/ms08_021_gdi_1.jpg](http://lh5.google.com/sunghun.hyun/R_xO1CR4saI/AAAAAAAAABo/ejz3kOul6Qg/s800/ms08_021_gdi_1.jpg)