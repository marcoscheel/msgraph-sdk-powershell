---
external help file:
Module Name: Microsoft.Graph.Identity.AdministrativeUnits
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.administrativeunits/update-mgadministrativeunitscopedrolemember
schema: 2.0.0
---

# Update-MgAdministrativeUnitScopedRoleMember

## SYNOPSIS
Update the navigation property scopedRoleMembers in administrativeUnits

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgAdministrativeUnitScopedRoleMember -AdministrativeUnitId <String> -ScopedRoleMembershipId <String>
 [-AdministrativeUnitId1 <String>] [-Id <String>] [-RoleId <String>] [-RoleMemberInfoDisplayName <String>]
 [-RoleMemberInfoId <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgAdministrativeUnitScopedRoleMember -AdministrativeUnitId <String> -ScopedRoleMembershipId <String>
 -BodyParameter <IMicrosoftGraphScopedRoleMembership> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgAdministrativeUnitScopedRoleMember -InputObject <IIdentityAdministrativeUnitsIdentity>
 -BodyParameter <IMicrosoftGraphScopedRoleMembership> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgAdministrativeUnitScopedRoleMember -InputObject <IIdentityAdministrativeUnitsIdentity>
 [-AdministrativeUnitId <String>] [-Id <String>] [-RoleId <String>] [-RoleMemberInfoDisplayName <String>]
 [-RoleMemberInfoId <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property scopedRoleMembers in administrativeUnits

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -AdministrativeUnitId
key: administrativeUnit-id of administrativeUnit

```yaml
Type: System.String
Parameter Sets: Update, UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -AdministrativeUnitId1
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -BodyParameter
scopedRoleMembership
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphScopedRoleMembership
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IIdentityAdministrativeUnitsIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RoleId
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RoleMemberInfoDisplayName
The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RoleMemberInfoId
Unique identifier for the identity.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ScopedRoleMembershipId
key: scopedRoleMembership-id of scopedRoleMembership

```yaml
Type: System.String
Parameter Sets: Update, UpdateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IIdentityAdministrativeUnitsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphScopedRoleMembership

## OUTPUTS

### System.Boolean

## ALIASES

## NOTES

### COMPLEX PARAMETER PROPERTIES
To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.

#### BODYPARAMETER <IMicrosoftGraphScopedRoleMembership>: scopedRoleMembership
  - `[Id <String>]`: Read-only.
  - `[AdministrativeUnitId <String>]`: 
  - `[RoleId <String>]`: 
  - `[RoleMemberInfoDisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
  - `[RoleMemberInfoId <String>]`: Unique identifier for the identity.

#### INPUTOBJECT <IIdentityAdministrativeUnitsIdentity>: Identity Parameter
  - `[AdministrativeUnitId <String>]`: key: administrativeUnit-id of administrativeUnit
  - `[DirectoryObjectId <String>]`: key: directoryObject-id of directoryObject
  - `[ExtensionId <String>]`: key: extension-id of extension
  - `[ScopedRoleMembershipId <String>]`: key: scopedRoleMembership-id of scopedRoleMembership
  - `[UserId <String>]`: key: user-id of user

## RELATED LINKS

