libjingle.patch: Libjingle has been modified to provide certificate based 
authentication

ipop.patch: ipop controllers has been modified to use certificate based 
authentication which is a new functionality added to libjingle with the patch

The base repositories for each of them are:
libjingle: http://webrtc.googlecode.com/svn/branches/3.52
ipop: https://github.com/ipop-project/ipop-tincan.git

The instructions for building the code after applying the respective patches
are present in the link 
https://github.com/ipop-project/documentation/wiki/Building-the-code-for-Linux

Other Committed Patches:
Also patches for certain portions of code which has been committed to ipop repo
already are also listed as separate patches here. The patches handle storing
credentials in a secure storage as well as interactive request for credentials.

The base for these patches is https://github.com/ipop-project/controllers

