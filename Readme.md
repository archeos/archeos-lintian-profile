# Lintian profile for ArcheOS

This package contains a Lintian specific profile for ArcheOS distribution.
For now this profile strictly inherits from Debian one. It only 
allows us to avoid the bad-distrib-in-changes-files error.  
Each new version name should be included in the 
vendors/archeos/main/data/changes-files/known-dist file.  

_To be discussed_
This package should be added as a build dependency for every other
packages.  

requirements and build instructions are detailed [here](
https://github.com/archeos/archeos-meta/blob/master/README.md)  

Lintian [documentation](http://lintian.debian.org/)
