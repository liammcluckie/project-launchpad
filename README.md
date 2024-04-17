# Current Personal Project Launchpad Setup

## Dependencies

-   npm
-   sass
-   http-server

## Code To Get Cracking

### Git / Github

-   `git init`

-   `git add .`

-   `git commit -m "Initial Commit"`

-   `git branch -M master`

-   `git remote origin add <repo link>`

-   `git push -u origin main`

### SASS Compiling

[Source](https://www.youtube.com/watch?v=pGcCWhl6ePQ)

-   `npm init -y`

<!-- Is this actually necessary?? -->

-   Update `package.json` file

```{
    "name": "Project Name",
    "version": "1.0.0",
    "description": "Project Description",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/liammcluckie/project-name.git"
    },
    "keywords": [],
    "author": "",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/liammcluckie/project-name/issues"
    },
    "homepage": "https://github.com/liammcluckie/project-name#readme",
    "devDependencies": {
        "node-sass": "^7.0.1"
    }
}
```

-   `sudo npm install -g sass`

-   The below command compiles SASS to the style.css file
<!-- TODO - create shortcut command for this -->
-   `sass --watch src/scss/main.scss:src/css/style.css`

### Localhost

[Source](https://devpractical.com/host-a-html-page-on-localhost/#nodejs-section)

-   `npm install http-server -g`

-   Navigate to folder where you have html file in terminal and type:

    -   `http-server`

    OR for a specific file

    -   `http-server name-of-file`

#### Update this project as needed!

## < / The End >
