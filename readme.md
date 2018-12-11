# Simply Memory Manager 1.61
****************************

Memory manager for Free Pascal and Lazarus. Suitable for simulation. 

Simply Memory Manager replaces native Free Pascal memory manager on Windows.

Works stable with Free Pascal and Lazarus on Windows x32 and x64.
On Ubuntu x64 and Xubuntu x32 works stable in single-thread mode with Free Pascal.


## How to use

Place "SimplyMM" the first after the statement "uses" like

    uses
      SimplyMM,
        ....
 
 
## SimplyMM and memory leaks tracing

Disable SimplyMM when using heap trace menager HeapTrc like

    uses
     // SimplyMM,
       .... 
 
 
## Links

Homepage: http://opensimply.org

SimplyMM is a part of [OpenSIMPLY project](https://sourceforge.net/projects/opensimply/)

Try it also. 