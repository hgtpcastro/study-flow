# 10. Configurando hooks no git
- [Repositório do Husky](https://github.com/typicode/husky)
- [Site oficial do Git sobre Hooks](https://git-scm.com/book/it/v2/Customizing-Git-Git-Hooks)

# Instalação Husky
```
npm install husky --save-dev
```
```
// package.json
{
  "husky": {
    "hooks": {
      "pre-commit": "npm test",
      "pre-push": "npm test",
      "...": "..."
    }
  }
}
```
