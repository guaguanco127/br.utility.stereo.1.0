# Max/MSP RNBO Patches for External of VST Creation: br.utility.stereo.1.0  
   
By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)  
Repository for br.utility.stereo.1.0, with all related filtes, can be found here: [https://github.com/guaguanco127/br.utility.stereo.1.0](https://github.com/guaguanco127/br.utility.stereo.1.0)  
Additional programs can be found here: [https://github.com/guaguanco127](https://github.com/guaguanco127)

These files were created with Max/MSP version 8.5.6. and RNBO 1.2.3

## Table of Contents 

[About](#About)   
[What is an External for Max/MSP?](#External)  
[What is a VST or AU Audio Plugin?](#VST)  
[How To Export as a Max/MSP External](#Export)  
[How To Export as a VST or AU Audio Plugin](#ExportVST)  

 
 

## <a name="About"></a>About

There are two Max/MSP patches in this folder.  

br.utility.stereo.rnbo.ext.1.0 is a patch set up to export as a Max/MSP external.  

br.utility.stereo.rnbo.vst.1.0.maxpat is a patch set up to export as a VST or AU audio plugin.  

Either program allows the user to adjust a the stereo mix of a signal. signal, such as swapping, left only, right only, mid, or side. Additionally, the user can adjust the width or the pan of the resulting signal.Currently works in any sample rate or bit depth.
  
**Modes:**   
**Stereo:** Normal stereo signal passes through  
**Swap:** This swaps the stereo signal, so the left is coming out of the right, and the right is coming out of the left  
**Left:** The left signal now plays through both the left and right  
**Right:** The right signal now plays through both the left and right  
**Mid:** Both signals added together and divided in half, in mono  
**Side:** A mono signal that consists of only signals that were in the stereo filed (sides) but not in the middle of the signal. 

**Pan:**  
Pans the stereo signal left (-100.0), midle (0.0), or right (100.0)

**Width:**  
Adjusts the width of of the stereo signal. 100. is normal stereo. 0. is a mono signal.
   

## <a name="External"></a>What is an External for Max/MSP?

An external is a type of object that does not come with your Max/MSP library. Unlike the typical objects that you can call on all versions of Max/MSP, an external must be installed on the users computer a specific way. 

## <a name="VST"></a>What is a VST or AU Audio Plugin? 

A VST is a third party audio plugin generally run within a digital audio workstation (DAW). A VST is cross platform for both Windows and Macintosh. An AU works the same way but is exclusively for Macintosh. 


## <a name="Export"></a>How To Export as a Max/MSP External

1. Make Sure Max/MSP 8 is installed in your computer, and make sure you have a license for RNBO as well.

2. Open up br.utility.stereo.rnbo.ext.1.0.maxpat using Max/MSP 

3. Double-click on the [rnbo~] object while the patch is locked.

4. Click on "Show Export Sidebar" on the right hand side 

5. Select "Max External Export"

6. Select settings needed to create a Max External. Make sure you name the object. 

## <a name="ExportVST"></a>How To Export as a VST or AU Audio Plugin

**Please note that you can only use an audio plugin on the same computer that you created it with RNBO. Sending an audio plugin to another computer will not work and be flagged as an unrecognized developer** 

1. Make Sure Max/MSP 8 is installed in your computer, and make sure you have a license for RNBO as well.

2. Open up br.utility.stereo.rnbo.vst.1.0.maxpat using Max/MSP 

3. Double-click on the [rnbo~] object while the patch is locked.

4. Select "Audio Plugin Export"

5. Select settings needed to create a VST (or AU), and select the platform. Make sure you name your plugin. 





    



 





