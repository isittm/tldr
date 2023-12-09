# Get-ChildItem

> List items in a directory.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/get-childitem>.

- List all non-hidden items in the current directory:

`Get-ChildItem`

- List only directories in the current directory:

`Get-ChildItem -Directory`

- List only files in the current directory:

`Get-ChildItem -File`

- List hidden items in the current directory:

`Get-ChildItem -Hidden`

- List all items in the current directory:

`Get-ChildItem -Force`

- List items in a directory other than the current one:

`Get-ChildItem -Path {{path\to\directory}}`
