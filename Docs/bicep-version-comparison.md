# Bicep PowerShell assemblies

Since Bicep PowerShell v1.3.0 the module is using the official [Bicep](https://github.com/Azure/bicep) assemblies. We generate our DLL:s by cloning the Bicep repo using the current release tag and performing a `dotnet publish` on the project to build the DLL:s. Below is a list of all Bicep PowerShell version showing which Bicep version is used for that specific release.

Bicep PowerShell version | Bicep CLI assembly version |
--- | --- |
`1.5.0` | `0.4.63` |
`1.4.7` | `0.3.539` |
`1.4.6` | `0.3.255` |
`1.4.5` | `0.3.255` |
`1.4.4` | `0.3.255` |
`1.4.3` | `0.3.126` |