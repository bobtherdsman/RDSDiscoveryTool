1-Download the Tool on c:\ drive 

2-extract the zip file on c:\RDSDiscoveryGuide

3-Once unzipped it should look like this:

c:\RDSDiscoveryGuide

    \c:\RDSDiscoveryGuide\IN
    
    \c:\RDSDiscoveryGuide\Out
    
4-"In" Directory will have a sample  "Serverstemplate" ,you need to create a txt file with all your servers , you can use IP , servername and if your port is not the 

    Default port enter the port as well  i.e servername,1435 or xxx.xxx.xxx.xxx,1435.

    save the file in the "In" directory. once the server list has been created, you should be ready to run the tool .

5-The tool will run from cmd prompt  as:

  Sql server Authentication 

	    c:\RDSDiscoveryGuide\RDSDiscovery.exe S  Login Password c:\RDSDiscoveryGuide\in\servers.txt
  
			   "Login"  should have access to the master table .
      
  Winsows Authentication 	

      c:\RDSDiscoveryGuide\RDSDiscovery.exe W c:\RDSDiscoveryGuide\in\servers.txt
    
The discovery will take few minutes and will generate an excel sheet .

The excel sheet is placed in c:\RDSDiscoveryGuide\out


    
