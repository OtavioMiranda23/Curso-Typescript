# Geral
- `function init(port) {}` -> port tem um tipo implícito any. Ts previne o implícito any.
- Aceita duck typing. Se o esperado é um Person { name: string }, é aceito um { name: string }
- É possíve ter os tipos ou os valores. `type person = { name: "Joao" | "Carlos" }`

## Tipagem de função
- É possível tipar uma callback como `Function`
- (param: string) => void

# Modulos
- É possível fazer o import apenas do type da classe com `import type X from "./x"`

# Namespace
- Sub sistema de modulos do ts