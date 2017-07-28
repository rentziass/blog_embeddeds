```
# edward.json
{
  "imports": [],
  "groups": [],
  "services": [
    {
      "name": "web",
      "path": "./web",
      "commands": {
        "build": "go build",
        "launch": "./web"
      }
    },
    {
      "name": "db_interface",
      "path": "./db_interface",
      "commands": {
        "build": "go build",
        "launch": "./db_interface"
      }
    }
  ]
}
```
