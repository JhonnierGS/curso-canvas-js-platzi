# curso-canvas-js-platzi

## **Table of Contents**
#### [Texto y dibujo en Canvas](https://github.com/pandao/editor.md "Heading link")



## Texto y dibujo en Canvas
- Para dibujar  en canavs usamos .fillRect y para borrar .clearRect
- Estos resiven 4 argumentos
  - eje X
  - eje Y
  - desde donde se va  a pintar o borrar en eje X
  - desde donde se va a pintar o borrar en eje Y

```javascript
  game.fillRect(0,50,100,100);
  game.clearRect(50,50,50,50);
  game.clearRect()
  game.clearRect(0,0,50,50);
```
- Tambien podemos hacer textos con .fillText este recibe 3 parametros
  - el texto que queremos escribir
  - eje X
  - eje Y 
```javascript
  game.fillText('Platzi', 25, 25);
```
- en los texto podemos usar funetes, estilos y alinear textos
```javascript
   game.font = '25px Verdana';
   game.fillStyle = 'purple';
   game.textAlign = 'center';
```
