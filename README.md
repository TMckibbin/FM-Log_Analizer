# FM-Log_Analizer
A FileMaker Pro solution to parse and more easily analyze the logs produced from FileMaker Server

Before importing, open the script workspace to script: "Import Logs"
  Change the 4 Import Records script steps to look in the desired file path where you will save the log files from the server
  
Export logs from server, unzip them and put them in the file path chosen above
From any of the main log screens, hit "Import..." button
Chose "Import all New logs" or select which logs you want and then hit "Import Selected Logs"

Note: each time you import logs the table that corresponds is first truncated before importing.
