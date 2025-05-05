ssh root@sa-vcsa-01.vclass.local
(logowanie root/VMware i akceptacja klucza)

uruchomienie shella

/usr/lib/vmware-vmca/bin/certificate-manager
opcja 3 :

root@sa-vcsa-01 [ ~ ]# /usr/lib/vmware-vmca/bin/certificate-manager
		 _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 
		|                                                                     |
		|      *** Welcome to the vSphere 8.0 Certificate Manager  ***        |
		|                                                                     |
		|                   -- Select Operation --                            |
		|                                                                     |
		|      1. Replace Machine SSL certificate with Custom Certificate     |
		|                                                                     |
		|      2. Replace VMCA Root certificate with Custom Signing           |
		|         Certificate and replace all Certificates                    |
		|                                                                     |
		|      3. Replace Machine SSL certificate with VMCA Certificate       |
		|                                                                     |
		|      4. Regenerate a new VMCA Root Certificate and                  |
		|         replace all certificates                                    |
		|                                                                     |
		|      5. Replace Solution user certificates with                     |
		|         Custom Certificate                                          |
		|         NOTE: Solution user certs will be deprecated in a future    |
		|         release of vCenter. Refer to release notes for more details.|
		|                                                                     |
		|      6. Replace Solution user certificates with VMCA certificates   |
		|                                                                     |
		|      7. Revert last performed operation by re-publishing old        |
		|         certificates                                                |
		|                                                                     |
		|      8. Reset all Certificates                                      |
		|_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _|
Note : Use Ctrl-D to exit.
Option[1 to 8]: 3

Please provide valid SSO and VC privileged user credential to perform certificate operations.
Enter username [Administrator@vsphere.local]:
Enter password:

Please configure certool.cfg with proper values before proceeding to next step.

Press Enter key to skip optional parameters or use Default value.

Enter proper value for 'Country' [Default value : US] : 

Enter proper value for 'Name' [Default value : CA] : 

Enter proper value for 'Organization' [Default value : VMware] : 

Enter proper value for 'OrgUnit' [optional] : 

Enter proper value for 'State' [Default value : California] : 

Enter proper value for 'Locality' [Default value : Palo Alto] : 

Enter proper value for 'IPAddress' (Provide comma separated values for multiple IP addresses) [optional] : 

Enter proper value for 'Email' [Default value : email@acme.com] : 

Enter proper value for 'Hostname' (Provide comma separated values for multiple Hostname entries) [Enter valid Fully Qualified Domain Name(FQDN), For Example : example.domain.com] : sa-vcsa-01.vclass.local

Enter proper value for VMCA 'Name' :VMCA      

You are going to regenerate Machine SSL cert using VMCA
Continue operation : Option[Y/N] ? : Y
Status : 100% Completed [All tasks completed successfully]             
