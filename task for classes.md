# Классы: работа со списком экземпляров


## Интро

Создайте класс “еда”, c названием Food  , он пригодится вам позже.

```Python
class Food:
    def __init__(self, name, cal, prots, fats, carbs):
        self.name = name # название
        self.cal = cal # калорийность
        self.prots = prots # белки
        self.fats = fats # жиры
        self.carbs = carbs # углеводы

products = [
	Food(name="сыр", cal=300, prots=11, fats=20, carbs=4),
	Food(name="курица", cal=165, prots=31, fats=3.6, carbs=0),
	Food(name="говядина", cal=250, prots=26, fats=16, carbs=0),
	Food(name="лосось", cal=206, prots=22, fats=13, carbs=0),
	Food(name="овсянка", cal=68, prots=2.5, fats=1.4, carbs=12),
	Food(name="банан", cal=105, prots=1.3, fats=0.4, carbs=27),
	Food(name="брокколи", cal=54, prots=3.7, fats=0.5, carbs=11),
	Food(name="арбуз", cal=30, prots=0.6, fats=0.2, carbs=6),
	Food(name="миндаль", cal=575, prots=21, fats=49, carbs=22),
	Food(name="шпинат", cal=23, prots=2.9, fats=0.4, carbs=3.6)
]
```
### Задание 1
Получите список всех названий еды в алфавитном порядке, отсортируйте и выведите первые 5 названий

```Python
# пример вывода

арбуз
банан
брокколи
говядина
курица
```

### Решение 1 способ

```Python
```
### Решение 2 способ

```Python
```



