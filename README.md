Name : Ritesh Kumar Ahirwar
Roll no : 23B0314

I have copied the same code as given in the assignment and have only made changes in the syncService class. 
The SyncService class represents a synchronization service that handles messages from devices.
It has an attribute aggregated_updates to hold the aggregated updates from all devices.
The onMessage method is called when the service receives a message from a device. If it's a probe request, the service responds with an update containing accumulated updates starting from the specified index. If it's a record, the record is stored in aggregated_updates.