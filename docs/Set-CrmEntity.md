---
external help file: AMSoftware.Crm.Powershell.Commands.dll-Help.xml
Module Name: AMSoftware.Crm
online version: https://github.com/AMSoftwareNL/crmpowershell/blob/master/docs/Set-CrmEntity.md
schema: 2.0.0
---

# Set-CrmEntity

## SYNOPSIS
Update an entity.

## SYNTAX

### SetEntityByInputObject (Default)
```
Set-CrmEntity [-InputObject] <EntityMetadata> [-PassThru] [<CommonParameters>]
```

### SetEntity
```
Set-CrmEntity [-Name] <String> [-DisplayName <String>] [-DisplayCollectionName <String>]
 [-Description <String>] [-Customizable <Boolean>] [-PassThru] [-CanChangeHierarchicalRelationship <Boolean>]
 [-CanEnableSyncToExternalSearchIndex <Boolean>] [-ChangeTrackingEnabled <Boolean>] [-EntityColor <String>]
 [-EntityHelpUrlEnabled <Boolean>] [-EntityHelpUrl <Uri>] [-IsInteractionCentricEnabled <Boolean>]
 [-IsKnowledgeManagementEnabled <Boolean>] [-IsOfflineInMobileClient <Boolean>]
 [-IsOneNoteIntegrationEnabled <Boolean>] [-IsOptimisticConcurrencyEnabled <Boolean>] [-IsSLAEnabled <Boolean>]
 [-SyncToExternalSearchIndex <Boolean>] [-HasNotes <Boolean>] [-HasActivities <Boolean>]
 [-AutoRouteToOwnerQueue <Boolean>] [-CanCreateAttributes <Boolean>] [-CanCreateCharts <Boolean>]
 [-CanCreateForms <Boolean>] [-CanCreateViews <Boolean>] [-CanModifyAdditionalSettings <Boolean>]
 [-IsActivityParty <Boolean>] [-IsAuditEnabled <Boolean>] [-IsAvailableOffline <Boolean>]
 [-IsConnectionsEnabled <Boolean>] [-IsDocumentManagementEnabled <Boolean>]
 [-IsDuplicateDetectionEnabled <Boolean>] [-IsMailMergeEnabled <Boolean>] [-IsMappable <Boolean>]
 [-IsRenameable <Boolean>] [-IsValidForQueue <Boolean>] [-IsVisibleInMobile <Boolean>]
 [-IconLargeName <String>] [-IconMediumName <String>] [-IconSmallName <String>] [<CommonParameters>]
```

## DESCRIPTION
Update an entity.

## EXAMPLES

## PARAMETERS

### -AutoRouteToOwnerQueue
Whether to automatically move records to the owner's default queue when a record of this type is created or assigned.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanChangeHierarchicalRelationship
Whether the hierarchical state of entity relationships included in your managed solutions can be changed.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanCreateAttributes
Whether additional attributes can be added to the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanCreateCharts
Whether new charts can be created for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanCreateForms
Whether new forms can be created for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanCreateViews
Whether new views can be created for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanEnableSyncToExternalSearchIndex
Whether this entity can be enabled for relevance search when customizing a managed solution.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanModifyAdditionalSettings
Whether any other entity properties not represented by a managed property can be changed.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChangeTrackingEnabled
Whether change tracking is enabled for an entity or not.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Customizable
Whether the entity is customizable.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The label containing the description for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayCollectionName
The label containing the plural display name for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The label containing the display name for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EntityColor
The color to be used for this entity in the application.

Any string matching a color in System.Drawing.Color.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EntityHelpUrl
The URL of the resource to display help content for this entity.

```yaml
Type: Uri
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EntityHelpUrlEnabled
Whether the entity supports custom help content.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HasActivities
Whether a custom entity is created that has a special relationship to activity entities and is a valid regarding object for the activity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HasNotes
Whether the custom entity that is created has a special relationship to the annotation entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IconLargeName
The name of the image web resource for the large icon for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IconMediumName
The name of the image web resource for the medium icon for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IconSmallName
The name of the image web resource for the small icon for the entity.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
The updated EntityMetadata object for the entity.

```yaml
Type: EntityMetadata
Parameter Sets: SetEntityByInputObject
Aliases: Entity

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsActivityParty
Whether the email messages can be sent to an email address stored in a record of this type.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsAuditEnabled
Whether auditing has been enabled for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsAvailableOffline
Whether the entity is available offline.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsConnectionsEnabled
Whether connections are enabled for this entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsDocumentManagementEnabled
Whether document management is enabled.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsDuplicateDetectionEnabled
Whether duplicate detection is enabled.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsInteractionCentricEnabled
Whether the entity is enabled for interactive experience.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsKnowledgeManagementEnabled
Whether Parature knowledge management integration is enabled for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsMailMergeEnabled
Whether mail merge is enabled for this entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsMappable
Whether entity mapping is available for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsOfflineInMobileClient
```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsOneNoteIntegrationEnabled
Whether OneNote integration is enabled for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsOptimisticConcurrencyEnabled
Whether optimistic concurrency is enabled for the entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsRenameable
Whether the entity DisplayName and DisplayCollectionName can be changed by editing the entity in the application.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsSLAEnabled
If the entity is enabled for service level agreements (SLAs).

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsValidForQueue
Whether the entity is enabled for queues.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsVisibleInMobile
Whether Microsoft Dynamics 365 for phones users can see data for this entity.

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The LogicalName of the entity to update.

```yaml
Type: String
Parameter Sets: SetEntity
Aliases: LogicalName

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns an object that represents the EntityMetadata. By default, this cmdlet does not generate any output.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SyncToExternalSearchIndex
Whether this entity is searchable in relevance search. 

```yaml
Type: Boolean
Parameter Sets: SetEntity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None
## OUTPUTS

### None
## NOTES

## RELATED LINKS

[Get-CrmEntity](Get-CrmEntity.md)

[New-CrmEntity](New-CrmEntity.md)

[Remove-CrmEntity](Remove-CrmEntity.md)

[EntityMetadata Class](https://msdn.microsoft.com/library/microsoft.xrm.sdk.metadata.entitymetadata.aspx)
