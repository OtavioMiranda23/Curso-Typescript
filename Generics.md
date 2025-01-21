# Generics
```
class Repository<T> {
  list: T[];
  constructor () { 
    this.list = [];
  }
  
  add (element: T) {
    this.list.push(element)
  }
}

class Person {
  constructor (readonly name: string, readonly age: number) {
  }
}

const persons = new Repository<Person>();
persons.add(new Person("Joao", 55));
```