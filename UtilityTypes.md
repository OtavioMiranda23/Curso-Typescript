# Utility Types
- `Partial<T>` torna parcial o uso de um tipo.
- `Pick<T, propriedade>` pega apenas a propriedade passada, seja uma ou mais.
- `Omit<T, propriedade1 | propriedade2 >` deixa de pegar apenas a propriedade, seja uma ou mais.
- `Required<T>` torna tudo o que está no tipo obrigatório, inclusive os propriedade?.
```
const keyboard = {
  keys: 100,
  connectionType: "usb"
} as const; // -> trava as propriedades do objeto, fica todo readonly

```