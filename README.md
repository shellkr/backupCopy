backupCopy
==========

A script utilizing the CopyCmd tool (Copy.com) and Dialog written in Bash for backing up directories on your system. 


Copy.com is basically just another Dropbox like service letting you save your files to the cloud. Besides Linux support it got a pretty awesome deal going right now when you refer
someone new to the service. It doesn't just give 5GB extra of storage to you but also to the one you refered. So if you like this script and haven't signed up yet then please use 
this referral link (https://copy.com?r=oN9cBn) to give us both some extra storage. One of the tools that Copy.com offer you is their CopyCmd command line client. This is the tool 
i utilize in this script. 

backupCopy is basically just a Bash script using Dialog (http://goo.gl/ZXRXM) to make it a bit more pretty. It will first ask you which directory you want to backup and then where 
to put it on Copy.com. It then compress the directory to a tar.xz file to make it smaller (about 50%), sends it to Copy and lastly ask if you want to keep the localy compressed 
file or delete it.
