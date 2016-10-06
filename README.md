# Automated Library prep for Spatial Transcriptomics
This repository contains the scripts neccesarry to run the Spatial Transcriptomics library preparation on a Magnatrix 8000+. The technology has been described by Ståhl et.al.

##Programs included 
Two programs are included. The first allows for parallel preparation of 1 to 8 samples and a second higher throughput program capable of preparing up to 16 samples. Each program consists of two parts. The first part takes the cDNA from the Spatial transcriptomics array and outputs the amplified RNA that is used as input in the second part. The second part of the programs outputs a sequencing library that is ready for multiplex library indexing. 

##Installation using the import function in Magnatrix OS
Download the ST_AMF.HXP file and log in to Magnatrix OS as a power user or administrator. Use the import guide, found in the Tools menu, and follow the on screen instructions.

##Manual installation
1. Open the AMF/PGF editor in Magnatrix OS.
2. Choose whether to create a new PFG file or modify an existing. 
3. Create a new Holder file for each part of the two programs.
4. Open the Holder editor and set the path for each downloaded file.  

##Points on transferring the progams to other liquid handling robots
Currently the automated protocol is only available on the Magnatrix platform. Other programs originally written for the Magnatrix system has been successfully transferred to the Agilent NGS workstation (https://github.com/ngi-automation). 

