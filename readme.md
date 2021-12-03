## Repository to reproduce issue:
```Parsing error: No Babel config file detected for somefile.js. Either disable config file checking with requireConfigFile: false, or configure Babel so that it can find the config files```

## How to
* Pull down repo
* `npm install`
* `npm run lint:js`

## Other
Works without having .eslintrc in repo, but I need / want this for the editor (vscode) to pick up what rules to use, also I usually override a couple of rules.