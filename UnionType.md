## Union Type
- Símbolo é o |
`type Age = number | string | boolean`
```
type Entity = {
  id: number
};

type Person = {
  name: string,
  age: number
};

type PersonEntity = Person & Entity
//ou
type PersonEntity = Person & { id: number }
```
```
type Entity = {
  id: number
};

interface Person extends Entity {
  name: string,
  age: number
};
```