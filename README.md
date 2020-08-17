# Powershelltricks

this is super neet to get only matched values from a file (line)
(Select-String .\DeepSecurityInventory_en.xml -Pattern Agent-.*11.0.*.zip )|foreach {$_.Matches.Value}

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\services\LanmanWorkstation\Parameters]
"DirectoryCacheLifetime"=dword:00000000
"FileInfoCacheLifetime"=dword:00000000
"FileNotFoundCacheLifetime"=dword:00000000

