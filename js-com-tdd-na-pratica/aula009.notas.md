# 9. Criando um Npm Script
- [Post sobre "Porque usar npm scripts?"](https://css-tricks.com/why-npm-scripts/)

# script .package.json
```
...
"scripts": {
    "lint": "./node_modules/.bin/eslint src/*.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },...
```
