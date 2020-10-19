# DataMungingService
This service gets data from a text file and writes to a SQL databse table 

In the DataMunging we have all scripts used to develop this service.

In the build folder there is a executable file named datamungingwinservice.
Once, double-clicked on this file the service will be running behind the scenes.

It is going to create two folder (Files and ProcessedFiles) in the path "C:\".

All text files should be pasted on folder Files to be processed. Once, this file is pasted 
the service will be executed and the file will be moved to folder ProcessedFiles.
