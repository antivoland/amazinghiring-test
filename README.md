# Тестовое задание

## 1

Есть два массива вида:

```
1,2,4,6,8,10
```

и

```
3,4,5,8,11,12
```

В качестве другого примера рассотрим массивы:

```
0,1,2,...100,200,201,202,...300
```

и

```
100,101,102...,200,300,301,302,...400,500
```

Их пересечение состоит из небольшого числа элементов:

```
100,200,300,400
```

Требуется найти пересечение (сложность в худшем случае составит O(N+M).

## 2

Для текста требуется определить его небулшитность. Это минимальное количество слов, выкинув которые из текста, мы получим выражение только из нашего словаря. Например:

```
Quick win by Search Engine Optimization Policy
```

Для этой фразы есть два варианта выкидывания слов. Выкинули 3 слова остальные выражения из словаря:

```
Quick win __ ______ ______ Optimization Policy
```

Выкинули 2 слова остальные выражения из словаря:

```
Quick win __ Search Engine Optimization ______
```

Не булшитность – 2.

Длина булшит фразы до 3 слов. 
