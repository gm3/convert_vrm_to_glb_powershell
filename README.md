# convert_vrm_to_glb_powershell
```curl
Get-ChildItem -Path $PWD -Filter *.vrm | ForEach-Object {Rename-Item $_.FullName -NewName ($_.Name -replace '\.vrm$','.glb')}
```
