# Решатель квадратных уравнений

Код решает квадратичные уравнения

# Как использовать

```python
from quadratic_equation import get_roots
...
root1, root2 = get_roots(value_a, value_b, value_c)
```
или
```python
import quadratic_equation
...
root1, root2 = quadratic_equation.get_roots(value_a, value_b, value_c)
```
где value_a, value_b, value_c - главный, средний и свободный коэффициенты квадратного уравнения.

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
