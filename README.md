# E2ESynapseDemo

Steps to deploy Demo Environment

1. Create ADLS Storage Account
2. Create SQL Server
3. Create SQL DW Pool under above SQL Server
4. Create Azure Data Factory (ADF)
5. Deploy ADF ARM template
6. Create tables in SQL DW
7. Load Data in Synapse
8. Connect PBI to Synapse
9. In SQLPool Firewallsettings, enable flag "Allow Azure services and resources to access this server"
Regenerate Master Key Passwird in Synapse "ALTER MASTER KEY REGENERATE WITH ENCRYPTION BY PASSWORD = '<Password>'"
  
