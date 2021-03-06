---
external help file: 
applicable: SharePoint Server 2013, SharePoint Server 2016
schema: 2.0.0
---

# Clear-SPScaleOutDatabaseTenantData

## SYNOPSIS
**Below Content Applies To:**SharePoint Server 2013

Applies to:

**Below Content Applies To:**SharePoint Server 2016

Removes all data related to the specified site subscription.



## SYNTAX

```
Clear-SPScaleOutDatabaseTenantData -ServiceApplication <SPServiceApplicationPipeBind>
 -SiteSubscriptionId <Guid> [-AssignmentCollection <SPAssignmentCollection>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Use the Clear-SPScaleOutDatabaseTenantData cmdlet removes all data related to the specified site subscription from the specified service application.

For permissions and the most current information about Windows PowerShell for SharePoint Products, see the online documentation at http://go.microsoft.com/fwlink/p/?LinkId=251831 (http://go.microsoft.com/fwlink/p/?LinkId=251831).

## EXAMPLES

### ------------EXAMPLE--------- (SharePoint Server 2013)
```
C:\PS>Clear-SPScaleOutDatabaseTenantData -ServiceApplication $serviceApplication -SiteSubscriptionId "5CAF2F99-A75F-4239-B9CD-7FE63D1CE904"
```

This example clears all data related to the site subscription with id 5CAF2F99-A75F-4239-B9CD-7FE63D1CE904 from the specified service application.

### ------------EXAMPLE--------- (SharePoint Server 2016)
```
C:\PS>Clear-SPScaleOutDatabaseTenantData -ServiceApplication $serviceApplication -SiteSubscriptionId "5CAF2F99-A75F-4239-B9CD-7FE63D1CE904"
```

This example clears all data related to the site subscription with id 5CAF2F99-A75F-4239-B9CD-7FE63D1CE904 from the specified service application.

## PARAMETERS

### -ServiceApplication
Specifies the service application in which to clear data.

```yaml
Type: SPServiceApplicationPipeBind
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteSubscriptionId
Specifies the site subscription id of the site subscription in which to clear data.

```yaml
Type: Guid
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AssignmentCollection
Manages objects for the purpose of proper disposal.
Use of objects, such as SPWeb or SPSite, can use large amounts of memory and use of these objects in Windows PowerShell scripts requires proper memory management.
Using the SPAssignment object, you can assign objects to a variable and dispose of the objects after they are needed to free up memory.
When SPWeb, SPSite, or SPSiteAdministration objects are used, the objects are automatically disposed of if an assignment collection or the Global parameter is not used.

When the Global parameter is used, all objects are contained in the global store.
If objects are not immediately used, or disposed of by using the Stop-SPAssignment command, an out-of-memory scenario can occur.

```yaml
Type: SPAssignmentCollection
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before executing the command.
For more information, type the following command: get-help about_commonparameters

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Displays a message that describes the effect of the command instead of executing the command.
For more information, type the following command: get-help about_commonparameters

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Export-SPScaleOutDatabaseTenantData]()

[Import-SPScaleOutDatabaseTenantData]()

