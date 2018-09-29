### Problem: число към бройна система

Да се напише метод **`IntegerToBase(number, toBase)`**, който получава като параметри цяло число и основа на бройна система и връща входното число, конвертирано към посочената бройна система. След това, резултатът да се отпечата на конзолата. Входното число винаги ще е в бройна система 10, а параметърът за основа ще е между 2 и 10.

#### Sample Input and Output

| Input | Output | Input | Output | Input | Output |
| --- |----| --- | --- | --- | --- |
|3<br>2|11|4<br>4|10|9<br>7|12|

#### Hints and Guidelines

За да решим задачата, ще декларираме стрингова променлива, в която ще пазим резултата. След това трябва да изпълним следните изчисления, нужни за конвертиране на числото.
* Изчисляваме **остатъка** от числото, разделено на основата.
* **Вмъкваме остатъка** от числото в началото на низа, представящ резултата.
* **Разделяме** числото на основата.
* **Повтаряме** алгоритъма, докато входното число не стане 0.

Допишете липсващата логика в метода по-долу:

```csharp
static string IntegerToBase(int number, int toBase) {
    string result = "";
    while (number != 0) {
        // Implement the missing conversion logic
    }
    return result;
}
```

#### Testing in the Judge System 

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/594#11](https://judge.softuni.bg/Contests/Practice/Index/594#11).