# Powershelltricks

this is super neet to get only matched values from a file (line)
(Select-String .\DeepSecurityInventory_en.xml -Pattern Agent-.*11.0.*.zip )|foreach {$_.Matches.Value}
