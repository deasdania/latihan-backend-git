

1. Install dependencies: `npm install`
2. Build the project: `npm run build`
3. Start the application: `npm start`


If node_modules/ has already been added to the repository (i.e., Git is already tracking the files), adding it to .gitignore will not stop Git from tracking the existing files. You'll need to untrack the files manually:

```
git rm -r --cached node_modules/
git commit -m "Stop tracking node_modules"
```