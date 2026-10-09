# geometric_lib

Библиотека для расчета геометрических параметров базовых фигур (круг, прямоугольник, квадрат, треугольник).

Полная документация по проекту, описание всех функций с примерами вызовов и история коммитов доступны в каталоге [docs/](docs/README.md).

## Быстрый старт

```python
from scripts.circle import area as circle_area
from scripts.rectangle import area as rect_area
from scripts.square import area as square_area
from scripts.triangle import area as tri_area

print("Площадь круга (r=5):", circle_area(5))
print("Площадь прямоугольника (3x4):", rect_area(3, 4))
print("Площадь квадрата (a=5):", square_area(5))
print("Площадь треугольника (a=6, h=4):", tri_area(6, 4))
```
