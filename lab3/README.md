SCSP
Если в очереди более одного элемента, то head и tail разотают с разными концами очереди => 
гонки данных не возникает. Иначе - делаем доп. проверку.

MCSP
На чтение всегда делаем доп. проверку из-за того, что несколько потоков могут разотать с одним
указателем (с одной ячейкой памяти - head). На запись нам потребуется доп. проверка, только если
в очереди меньше 1 элемента.

## Варианты заданий

 Номер | Виды структур | Баллы |
|:------|:--------------|:------|
| 17    | 5, 6          | 11    |

