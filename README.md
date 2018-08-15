# TeamViwer-V13
echo "Installing TeamViwer in RedHat Enterprise Linux in 7.4"
#########Welcome to TeamViwer Installation############
#Installation step's
#First :- Install the qt5-qtwebkit-5.6.2-1.el7.x86_64.rpm Package
yum install qt5-qtwebkit-5.6.2-1.el7.x86_64.rpm -y
#Second :- install the teamviewer_13.1.3026.x86_64.rpm Package
yum install teamviewer_13.1.3026.x86_64.rpm -y

#Instead of RHEL7.4 you have a some other RHEL7.X(some minor version) means you can do follow steps

#create a local repo using the RHEL7.4 ISO
#After you can do installation step's
