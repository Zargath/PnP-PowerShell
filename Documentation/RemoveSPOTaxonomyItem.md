#Remove-SPOTaxonomyItem
Removes a taxonomy item
##Syntax
```powershell
Remove-SPOTaxonomyItem [-Force [<SwitchParameter>]] -TermPath <String>
```


##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
|Force|SwitchParameter|False||
|TermPath|String|True|The path, delimited by | of the taxonomy item to remove, alike GROUPLABEL|TERMSETLABEL|TERMLABEL|
