# 6. Instalando e Usando o Eslint
- [Post meu sobre "Analisando seu código js com linter"](https://willianjusten.com.br/analisando-seu-codigo-js-com-linter/)
- [Sublime Linter](http://www.sublimelinter.com/en/latest/)
- [Atom Eslint](https://github.com/AtomLinter/linter-eslint)

# Diversos
- [Style guides Javascript com ESLint, Prettier e EditorConfig | Diego Fernandes](https://www.youtube.com/watch?v=TI4v4Y8yRjw)
- [ESLint VSCode RocketSeat](https://github.com/Rocketseat/youtube-style-guide-javascript)

# Comandos

# Instalar o ESlint como dependencia do projeto (global, vai obrigar a todos instalar globalmente)
```
npm install eslint --save-dev
```
# Iniciar o ESLint - cria o arquivo: .eslintrc.json
```
./node_modules/.bin/eslint --init
```
# Iniciar o ESLint - cria o arquivo: .eslintrc.json (Windows)
```
.\node_modules\.bin\eslint --init
```

# Com npx (vai instalr o eslint temporariamente, e executalo)
```
npx eslint
```

# Rodar o ESLint (Windows)
```
.\node_modules\.bin\eslint src\*.js
```
