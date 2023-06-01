# Fullstack Engineer Assessment - IP Address Management


## REST API
An IP Address Management REST API on top of any data store of your choice. It has the ability to add IP Addresses by CIDR block and then either acquire or release IP addresses individually. Each IP address will have a status associated with it that is either “available” or “acquired”.

## The REST API supports four endpoints:

* Create IP addresses - take in a CIDR block (e.g. 10.0.0.1/24) and add all IP addresses within that block to the data store with status “available”
* List IP addresses - return all IP addresses in the system with their current status
* Acquire an IP - set the status of a certain IP to “acquired”
* Release an IP - set the status of a certain IP to “available”


## Frontend
Create a frontend application using frontend technologies such as HTML, CSS, JavaScript.
Make sure to utilize the REST API you created in the previous section.


## Bonus
Deploy the Application to a Cloud provider (ex. AWS or Azure).
