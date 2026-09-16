# Crowdstrike_detecting_falconflank
Crowdstrike Query to lookup if any of host is impacted by FalconFlank.
Hunting includes 3 steps process.
1)We Hunt for file writes/drops of bcrypt.dll in the Pwsh directory 
2) We Hunt for MareBackup scheduled task (Creation/Execution)
3) We Hunt for Explicit named pipe creation/interaction containing FALCONFLANK
