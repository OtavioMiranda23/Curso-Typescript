# Any x Unknown x Never
- Unknown: Não se pode declarar unknown e depois atribuir um tipo conhecido. Uma vez declado, é preciso permanecer unknown
- Never: Nunca vai retornar, não chegará no final da função. Void é retorno vazio.
```
function init(): never {
  while (true) {

  }
}
function init(): void {
  return undefined;
}
```