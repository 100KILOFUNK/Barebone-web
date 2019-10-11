# Barebone web project

Tech:
* Node.js
* Jade engine for HTML rendering.


First time:
```
$ > npm install     # Will install dependencies stated in the package.json file
```

All the other times:
```
$ > npm start       # Start the Node.js Server, default is 127.0.0.1:3000.
```

Run these commands in the Root directory of the project.

## Folder structure

```
/
├── bin
├── DB
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets         # Contains some css for reactive coding (Column division and @media)
├── routes
└── views
    ├── error.jade          # Error renderer
    └── layout.jade         # Dependencies (Stylesheet, scripts). Extend this to every Jade file.

```


