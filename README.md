# Npm package layout download
    git pull https://github.com/mdmurshed/npm-layout.git

# Folder structure
    dist 
    -> In dist folder auto store the js file when compile the react component
    src
    -> In src file create your own component
    # example:
    React component (.js) file
    Index.js (import the react component to the index.js)
    .gitignore
    README.md
    package-lock.json
    package.json
    Rollup.config.js

# Publish your own package
    Step 1: npm i npm-layout
    Step 2: set the component
    Step 3: npm run build-lib
    Step 4: in cli “npm login”
    Step 5: fill the username and password 
    Step 6: npm publish
