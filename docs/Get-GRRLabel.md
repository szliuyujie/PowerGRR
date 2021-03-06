---
external help file: PowerGRR-help.xml
online version: 
schema: 2.0.0
---

# Get-GRRLabel

## SYNOPSIS
Get all labels.

## SYNTAX

```
Get-GRRLabel [-Credential] <PSCredential> [-ShowJSON] [<CommonParameters>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### Example 1
```
PS C:\> Get-GRRLabel -Credential $creds
```

Return every label which is available in GRR.

### Example 2
```
PS C:\> Get-GRRLabel -Credential $creds | sls osx
```

Return every available label which contains "osx".

## PARAMETERS

### -Credential
GRR credentials.

```yaml
Type: PSCredential
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ShowJSON
{{Fill ShowJSON Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Keine

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

