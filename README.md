# Анализ статистики продаж
*Инструмент будет полезен менеджерам по продажам и предпринимателям*

**Возможности инструмента:**
* Сохранение каждой продажи в элемент массива
* Подсчет дней с наибольшим количеством продаж


*Разработан на:*
[JDK 17](https://openjdk.org/projects/jdk/17/)

 Фрагмент кода:
```java
  public int max() {
        int max = -1;
        for (int sale : sales) {
            if (sale > max) {
                max = sale;
            }
        }
        return max;
    }
```
