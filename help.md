# File Explorer
Project by [Anosema](https://github.com/Anosema/FileExplorer)


## How to config
You can custom your explorer by modifying [config.json](config.json)
```json
//" If true, hidden files (starting with a .) will be shown" 
"showHidden": true,
// Directory list, those directories will always show hidden files: 
"hideExceptions":[
],
// Directory list, those directories will always hide hidden files: 
"showExceptions":[
],
// Layout mode, choose between:
// - list
// - grid
"layout": "list",
"informations":[
	""
]
```

## TODO

- Add informations: ctime mtime atime
- Integrate path line