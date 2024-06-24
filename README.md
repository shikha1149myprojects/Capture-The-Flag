You have been hired to conduct a penetration test and security assessment for a fictitious company, ENPM685 Pictures, Inc. The goal of this penetration test and security assessment is to show the executive of ENPM685 Pictures, Inc. that their security posture needs to be improved.

 

Background
 

ENPM685 Pictures, Inc. is a small movie production studio that specializes in low budget “mockbusters” that are spoofs of larger budget films produced by larger studios. They have been successful by extreme cost cutting wherever possible, which shows in their IT infrastructure and hiring practices. For example, to not have to deal with employee benefits the company only has 1 employee, the CEO Bob Dobbs. Everyone else is hired as a contractor. Due to a recent issue with a rogue contractor stealing several ideas for upcoming films and an aggressive growth plan the CEO is moving towards hiring actual employees and developing the infrastructure (IT and otherwise) that supports ENPM685 Picture, Inc’s production efforts.

 

As part of this expansion, I as a consultant to the CEO has recommended bringing in an IT security firm to assess the current state of ENPM685 Pictures, Inc’s IT security through a penetration test of the current environment. You are a Security Consultant who works for the IT security firm hired to perform this assessment.

 

Build a Replica of the Server
 

ENPM685 Pictures, Inc’s IT operations are small -- a single server that hosts the firm’s website, primary file server, as well as other resources. You can build your own copy of this server by doing the following steps.

 

The virtual machines for this midterm are in the class Google Drive link - https://drive.google.com/drive/u/1/folders/1ziMDTG6ItZxIT5QjaEvHvs-8rk1xKsF_Links to an external site. There are options for x64 (Windows and Intel-based Macs using VMware) and Apple's M chips (VMware and Parallels)

 

x64 users (Windows and Intel-based Macs)
 

Download the .ova file from the class Google Drive share 
In VMWare menu select File and then Import…
Select the .ova file for the VM you wish to import and click Continue
Give the VM a name (ex: “ENPM685 - Midterm - Ubuntu”)
Click Save
Once the VM has finished importing click Finish
If you get a popup saying there were issues select Retry and the VMs should import.
Click the Play button in the VM window to start it
 

ARM64 users (M1-based Macs - VMware)
 

1. Download the Midterm ZIP file from the class Google Drive share

2. Copy the ZIP file to your Virtual Machines folder (this is a directory under your username folder in macOS.)
3. Double click the ZIP file to unzip it

4. Once the file has uncompressed delete the ZIP file to save space on your computer
5. Double click the “ENPM685 Midterm” file (VMbundle) to import and start the VM.

Note: if asked if you Moved or Copied the VM select “Moved”

 

ARM64 users (M1-based Macs - Parallels)
1. Download the ENPM685 Midterm.pvm.zip file from the class Google Drive share
2. Copy ENPM685 Midterm.pvm.zip to your Parallels folder (this is a directory under your username folder in macOS.
3. Double click the ENPM685 Midterm.pvm.zip file to unzip it
4. Once the file has uncompressed delete the ENPM685 Midterm.pvm.zip file to save space on your computer
5. Open Parallels and in the File menu select “Open...”
6. Select the ENPM685 Midterm.pvm file and start up the VM.
Note: if asked if you Moved or Copied the VM select “Moved”

If you have questions about this process review Parallel’s documentation on this process here: https://kb.parallels.com/114118

 

The Assignment and Requirements
 

Conduct a penetration test of ENPM685 Pictures, Inc’s server and report your findings.
You are not being provided any credentials for this server.  You'll find to find a way to break into the server.
There are 6 “flags” spread out across the server. By finding these you can demonstrate to the CEO the need to make security improvements. A top grade can only be attained by finding all 6 flags.
What is a flag? It will be a short phrase or other interesting information you discover during your penetration test. For example, if the flag is a file (named “flagX_is_inside” it will be the contents of the file, not just the file name/location. They are clearly marked, you will know them when you see them.
If a file is a flag the CONTENT of the file is the actual flag, not just the file name
Flags are not in any order; you don’t need to find them in any specific order
 

The Rules of Engagement
 

Use any tools you feel are appropriate to properly test ENPM685 Pictures, Inc’s computers for security vulnerabilities.
Booting the VM into a single user/recovery mode is NOT PERMITTED.
Changing a password of any kind is NOT PERMITTED.
 
