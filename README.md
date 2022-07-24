# Safe

Safe é um fork da versão [9.0.10](https://github.com/roots/sage/releases/tag/9.0.10) do [Sage](https://github.com/roots/sage), a última antes das mudanças que vieram com a versão 10.

Compatível com [Bun](https://bun.sh/) que é muito mais rápido que o [yarn](https://yarnpkg.com/) e com menos dor de cabeça na hora de instalar e buildar o projeto.

É recomendável usar a versão 12.x do Node:
```bash
nvm install 12
nvm use 12
```
Caso você tenha um erro com o package `node-sass` rode o commando de rebuild para corrigir o binário no seu sistema operacional:
```bash
bun run build:rebuild
```
ou 
```bash
yarn build:rebuild
```
