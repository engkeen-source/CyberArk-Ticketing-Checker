# CyberArk-Jira-Integration

1. Clone the repository
2. Add reference to the current solution
  - CyberArk.PasswordVault.PublicInterfaces.dll (copy from PVWA Bin Folder)
  - Newtonsoft.Json.dll v11.0.2 (depend on your PVWA version, go to PVWA Bin Folder, right click the dll file and check)
  - RestSharp.dll v106.13.0.0 (latest as of Dec 2021)
<img width="207" alt="image" src="https://user-images.githubusercontent.com/71132168/231621038-d729fe93-787a-4371-aa42-3f32fa008f70.png">

3. Ensure .NET framework is 4.8
<img width="689" alt="image" src="https://user-images.githubusercontent.com/71132168/231620765-5416c5af-1105-4db6-a632-c778766a8571.png">

4. Build the solution, dll will be located in the debug folder.
<img width="546" alt="image" src="https://user-images.githubusercontent.com/71132168/231620939-43c1f6f0-90e3-40bf-902a-6c165eb03ebc.png">


5. Copy this dll to PVWA Bin folder.

# Function Implemented
1. Validate ticket pattern only
  - based on regex












