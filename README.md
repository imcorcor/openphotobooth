# openphotobooth
An opensource photobooth software directed at use for weddings and parties. 

Currently, there is no good open-source solution for a wedding-style photobooth. The goal
of this project is to provide an open-source photo booth that is easy to set up and run. 

# Known problems

- There is a bug when install SimpleCV on Ubuntu 16.04
The pyton-support package needs to be installed before 
installing SimpleCV using 
`wget http://launchpadlibrarian.net/109052632/python-support_1.0.15_all.deb
sudo dpkg -i python-support_1.0.15_all.deb`
