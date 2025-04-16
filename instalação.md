# instalação sass

1. instalar o node: npm init -> npm install
2. instalar o sass em desenvolvimento: npm i --save-dev sass
3. criar o arquivo .gitignore
4. ignorar a pasta node_modules
5. adicionar o sass ao script do package.json: script { "sass": "sass ./source/main.scss ./build/main.css --watch"}
6. iniciar o sass usando o node: npm run sass main.scss main.css
