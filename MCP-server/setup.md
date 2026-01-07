create a .vscode/mcp.json file in the workspace and add similar content
```
 {
   "servers": {
     "filesystem": {
       "command": "npx",
       "args": [
         "-y",
         "@modelcontextprotocol/server-filesystem",
         "./.vscode"
       ]
     }
   }
 }
```
note the keys in json should be similar and are specific for vscode

* now wait some time it automatically shows the start button in that json file
* mcp servers usually installed with uvx or npx the server code is automatically fetched from package repositories and executed with out manual configuration 
* you can also add mcp server by adding the above json content in workspace or user setting json
* the mcp servers can also be installed as extension although it also crete the same mcp.json in .vscode/