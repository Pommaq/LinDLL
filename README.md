# LinDLL
A project intended to implement Windows .dll support natively in Linux. Not some wine emulation shit.

TODO/What do we want it to do?:
  * It has to run from the kernelspace.
  * Not intended to "port" windows programs to linux. Merely create support for .dll
  * Figure out how .dll files are structured and how we can use them from a kernel point of view
  * Figure out how a .exe file is structured and how to make them use our .dll files.
  
