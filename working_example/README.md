* Either change the URL in all the settings or edit your hosts file to resolve elabftw.dus to localhost
* Run the script in pxc/init
* Set all the PXC data and the content of the volumes to be owned by uid 1001
* Create the volume for pxc1
* Copy a mysql database to the volume
* Start pxc1, when it runs then pxc2 and pxc3, then everything else 
* When the cluster has been started once you can start/stop everything at once