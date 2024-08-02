# Azurelight
```
local function executeAzureScript()
    
    local AzureScript = game:HttpGet("https://raw.githubusercontent.com/Eradate/Azurelight/main/AzureBlade.txt")
    
       local scriptFunction = loadstring(AzureScript)
    
    if scriptFunction then
        scriptFunction()
    else
        print("Failed to load script.")
    end
end

executeAzureScript()
```

Anyways here
