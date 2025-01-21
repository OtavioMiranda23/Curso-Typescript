# Decorators
- Pode se ter decorator de classe, método, propriedade, parâmetro
- Deve-se criar uma função com o mesmo nome do decorator
- Sempre volta uma função trazendo o protype do objeto, como:
```
 return (constructor: Function) => {
  constructor.prototype.propriedade...
 }
```
 - Se declara propriedade dinâmicas no TS com: 
 `[key: string]: any`