# Enums 
```
export enum Categories {
  PROGRAMMING, 
  SCIENCE,
  ENTERTAINMENT
}
Categories.PROGRAMMING -> 0 //índice
```
```
export enum Categories {
  PROGRAMMING = "Programming", 
  SCIENCE = "Science",
  ENTERTAINMENT = "Entertainment"
}
Categories.PROGRAMMING -> "Programming" //valor
```