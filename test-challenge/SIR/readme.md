# SIR #
## Scan, Interrogate & Report ##

Phase I) Produce list of active device IPs<br>
>**input:** a subnet in the form a.b.c.d/e<br>
>**output:** 2 CSV files, 1 of up IPs and 1 of down IPs<br>
>**methods:** calculate the number of IPs to be tested and provide a progress meter during the scanning 

Phase II) Interrogate active IP list produced from Scan Phase I<br>
>**input:** a CSV file of active IPs<br> 
>**output:** a file per IP of machine information<br>
>**methods:**<br>
>1) each file name must include IP and date<br>
>2) Hardware information including manufacturer, model, CPU, RAM and local disk sizes<br> 
>3) The date of the last hotfix applied to the machine and last reboot time<br>
>4) If any of the following are installed:<br>
- IIS<br>
- SQL Server<br> 
- Exchange<br>
- SharePoint<br>
>5) Installed Windows components

Phase III) Report on a selected machine and produce a PowerPoint of collected data