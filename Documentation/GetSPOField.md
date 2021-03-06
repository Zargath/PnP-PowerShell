#Get-SPOField
Returns a field from a list or site
##Syntax
```powershell
Get-SPOField [-List <ListPipeBind>] [-Web <WebPipeBind>] [-Identity <FieldPipeBind>]
```


##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
|Identity|FieldPipeBind|False|The field object or name to get|
|List|ListPipeBind|False|The list object or name where to get the field from|
|Web|WebPipeBind|False|The web to apply the command to. Omit this parameter to use the current web.|
##Examples

###Example 1
```powershell
PS:> Get-SPOField
```
Gets all the fields from the current site

###Example 2
```powershell
PS:> Get-SPOField -List "Demo list" -Identity "Speakers"
```
Gets the speakers field from the list Demo list
