﻿{% hint style="info" %}
Universal Dashboard is now a part of PowerShell Universal. This documentation is for reference to the v2 version of Universal Dashboard and is no longer maintained. PowerShell Universal Documentation can be found [here](https://docs.ironmansoftware.com).
{% endhint %}


---
external help file: UniversalDashboard.dll-Help.xml
Module Name: UniversalDashboard
online version: https://go.microsoft.com/fwlink/?LinkID=217032
schema: 2.0.0
---

# Get-UDAuthorizationPolicy

## SYNOPSIS
Returns authorization policies that the user passes.

## SYNTAX

```
Get-UDAuthorizationPolicy [<CommonParameters>]
```

## DESCRIPTION
Returns authorization policies that the user passes.

## EXAMPLES

### Example 1
```
$Policies = Get-UDAuthorizationPolicy 
if ($Policies -contains 'Administrator') {
    New-UDCard -Title 'Administrator' -Content {}
}
```

Returns a card if the user has the Administrator authorization policy. 

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS



