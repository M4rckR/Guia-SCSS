### Guia de sass

Comando para utilizar sass con bs: `npm i --save-dev bootstrap sass`


Para hacerlo sin gulp y demas podemos tener el json asi: 

```json
{
  "name": "03-meeti",
  "version": "1.0.0",
  "description": "Aprendiendo bootstrap 5 y sass",
  "main": "index.js",
  "scripts": {
    "compilar:sass": "sass src/scss:build/css"
  },
  "author": "Marcos Romero",
  "license": "ISC",
  "devDependencies": {
    "bootstrap": "^5.3.3",
    "sass": "^1.83.0"
  }
}

