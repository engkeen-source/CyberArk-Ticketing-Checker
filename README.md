# CyberArk-Jira-Integration

1. Clone the repository
2. Add reference to the current solution
  - CyberArk.PasswordVault.PublicInterfaces.dll (copy from PVWA Bin Folder)
  - Newtonsoft.Json.dll v11.0.2 (depend on your PVWA version, go to PVWA Bin Folder, right click the dll file and check)
  - RestSharp.dll v106.13.0.0 (latest as of Dec 2021)
3. Ensure .NET framework is 4.8
4. Build the solution, dll will be located in the debug folder.
5. Copy this dll to PVWA Bin folder.

# Function Implemented
1. Validate ticket pattern only
  - based on regex












