---
external help file: 
applicable: SharePoint Online
schema: 2.0.0
---

# Disconnect-SPOService

## SYNOPSIS
Disconnects from a SharePoint Online service.

## SYNTAX

```
Disconnect-SPOService [<CommonParameters>]
```

## DESCRIPTION
The Disconnect-SPOService cmdlet explicitly disconnects a previously created SharePoint Online service connection.

Global administrators can disconnect the service by running the Disconnect-SPOService cmdlet or by running the Connect-SPOService cmdlet to initiate another connection.
For more information, see Connect-SPOService.

Even after a connection is terminated, operations that were started before the connection is terminated will run to completion.
In other words, long-running operations will not be terminated by running the Disconnect-SPOService cmdlet or the Connect-SPOService cmdlet.

You must be a SharePoint Online global administrator to run the cmdlet.

For permissions and the most current information about Windows PowerShell for SharePoint Online, see the online documentation at http://go.microsoft.com/fwlink/p/?LinkId=251832 (http://go.microsoft.com/fwlink/p/?LinkId=251832).

## EXAMPLES

###   (SharePoint Online)
```

```

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Introduction to the SharePoint Online management shell]()

[Set up the SharePoint Online Management Shell Windows PowerShell environment]()

[Get-SPOAppErrors]()

[Connect-SPOService]()

[Online Version](http://technet.microsoft.com/EN-US/library/efd0e73c-1cb1-4dd4-83ea-cedec565ba24(Office.15).aspx)

