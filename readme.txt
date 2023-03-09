ServiceAccountUpdate is a PowerShell script update extension .ps1 that iterates over a list of servers, stops a list of services on each server, changes the service account and password for each service, and then starts the services in a specified order.

Here is a breakdown of what the script is doing:

The script prompts the user for a username to update and a server password. 

The script defines a list of servers by reading the contents of a text file.

The script defines a list of services and a start sequence for the services.

The script iterates over each server in the list of servers.

For each server, the script starts the services in the specified order.

Note: This script assumes that the user running the script has administrative privileges on each server and has the appropriate permissions to change service accounts and passwords. It also assumes that the list of servers and the list of services are accurate and up-to-date.
It also dump html report for easy refernce 
============
Define the list of servers 
"C:\Scripts\Allservers.txt"

