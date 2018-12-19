## Installing CNTK on Windows

#### Before you begin
 * Do I have to do this?
   - No, this is only needed if you want to take advantage of GPU computing
 * Will this work on any computer
   - No, it only works if you have a GPU that can be used by CNTK
 * How large is it?
   - CNTK will download several GB of data during installation.
 * Any prerequisites?
   - CNTK comes with its own Anaconda, if you already have an Anaconda installation you may want to remove it. CNTK might be able to use your existing Anaconda, but the installation instructions are surprisingly specific about the Anaconda version CNTK needs.

Note: 

#### Download and installation
 - Download the zip file from here (click I agree) - https://cntk.ai/dlwg-2.6.html
 - Unzip
 - cd to cntk\Scripts\install\windows\
 - Run `install.bat  -AnacondaBasePath E:\Anaconda3 -PyVersion 36`
    - Replace E:\Anaconda3 with the path where you want Anaconda to be installed
 - When done, the script will display some info, the useful part is the location of the activation script:
   - <dir were you unzipped cntk>\cntk\scripts\cntkpy36.bat  

