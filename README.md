Download the Tool on c:\ drive 
extarct the zip file on c:\RDSDiscoveryGuide
the tool comes  with RDSDiscovery.exe , In and Out Directory 
once unzipped it should look like this
c:\c:\RDSDiscoveryGuide
    \c:\RDSDiscoveryGuide\IN
    \c:\RDSDiscoveryGuide\Out.
"In" Directory will have a sample  "Serverstemplate" ,you need to create a txt file with all your servers , you can use IP , servername and if you port is not a default port enter the port as well  as servername,1435 or xxx.xxx.xxx.xxx,1435. save the file in the "In" directory.
once the server list has been created, you should be ready to run the tool .
the tool will run from cmd
c:\RDSDiscoveryGuide\RDSDiscovery.exe Login Password c:\RDSDiscoveryGuide\in\servers.txt
"Login"  should have access to the master table .
The discovery will take few minutes and generate an excel sheet with all the edition and features used by sql server on prem.

    
