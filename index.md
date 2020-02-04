### GD32 Development Board With LCD from Seeed Studio Project

When I got this board, I could not get the demos to compile.  I found 
that I needed to add the arduino framework mentioned in the library 
that was found on github.  After adding this I found that some additional headers were missing, such as String.h.  So, I did a search and found that the riscv tools was available on github with the newlib library which I hope has these standard libary functions needed to finish the arduino framework compile.  

So this page will be used to host the repository for the toolkit with newlib in it. 


