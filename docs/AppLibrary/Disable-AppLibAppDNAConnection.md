﻿# Disable-AppLibAppDNAConnection

   Disables Citrix Studio integration with AppDNA.

## Syntax
```
Disable-AppLibAppDNAConnection [-LoggingId <Guid>] [-AdminAddress <String>] [<CommonParameters>]
```

## Detailed Description
   Disables Citrix Studio integration with the configured AppDNA connection.

## Related Commands
  * [Enable-AppLibAppDNAConnection](Enable-AppLibAppDNAConnection.html)
  * [Get-AppLibAppDNAConnection](Get-AppLibAppDNAConnection.html)
  * [Set-AppLibAppDNAConnection](Set-AppLibAppDNAConnection.html)
  * [Remove-AppLibAppDNAConnection](Remove-AppLibAppDNAConnection.html)
## Parameters

| Name   | Description | Required? | Pipeline Input | Default Value |
| --- | --- | --- | --- | --- |
| LoggingId | Specifies the identifier of the high-level operation this cmdlet call forms a part of. Citrix Studio and Director typically create high-level operations. PowerShell scripts can also wrap a series of cmdlet calls in a high-level operation by way of the Start-LogHighLevelOperation and Stop-LogHighLevelOperation cmdlets. | false | false |  |
| AdminAddress | Specifies the address of a XenDesktop controller the PowerShell snap-in will connect to. You can provide this as a host name or an IP address. | false | false | Localhost. Once a value is provided by any cmdlet, this value becomes the default. |

## Input Type
### 
   
## Return Values
### void
   ## Notes
   The configured connection details are not removed or modified in anyway, only disabled.
## Examples

### EXAMPLE 1
```
C:\PS>Disable-AppLibAppDNAConnection
```
   Description<br>-----------<br>Disables Citrix Studio integration with the configured AppDNA connection.
