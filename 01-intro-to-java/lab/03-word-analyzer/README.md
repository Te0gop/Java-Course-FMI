## Общи букви :abc:

### Условие

Създайте публичен клас `WordAnalyzer` с метод

```java
public static String getSharedLetters(String word1, String word2)
```

който по дадени два символни низа, връща низ, съдържащ само символите, които се срещат и в двата низа. Входните низове съдържат само малки и главни латински букви, като при сравнението на низовете, разликата в капитализацията на буквите се пренебрегва. Резултатният низ трябва да е сортиран лексикографски. Ако няма общи символи между двата низа, трябва да се върне празен низ.

### Примери

| Извикване                            | Резултат |
|:------------------------------------ |:-------- |
| `getSharedLetters("house", "home")`  | `"eho"`  |
| `getSharedLetters("Micky", "mouse")` | `"m"`    |
| `getSharedLetters("house", "villa")` | `""`     |