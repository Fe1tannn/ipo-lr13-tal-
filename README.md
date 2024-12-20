# Общие задания

---

## Задание 1

- Создать два связанных класса:
    - **ImageHandler** — класс для базовой работы с изображениями (загрузка, сохранение, изменение размеров и форматов).
    - **ImageProcessor** — класс для обработки изображения (применение фильтров, добавление текста, поворот).
- Класс **ImageHandler** должен:
    - Принимать путь к изображению при инициализации.
    - Содержать методы для загрузки изображения, сохранения и изменения его размера.
    - Обеспечивать передачу изображения в класс **ImageProcessor**.
- Класс **ImageProcessor** должен:
    - Принимать изображение, переданное из **ImageHandler**.
    - Содержать методы для применения различных фильтров, добавления текста и других эффектов.

<aside>
🚨

В каждом классе нужно реализовать свой функционал, указанный в варианте далее

</aside>

## Задание 2
### **Вариант 2**

1. В классе **ImageHandler**:
    - Реализовать метод для загрузки изображения и поворота его на 90 градусов.
    - Реализовать метод для обрезки изображения (crop) до размера 150x150 пикселей.
2. В классе **ImageProcessor**:
    - Применить чёрно-белый фильтр (convert('L')).
    - Добавить текст "Вариант 2" в верхнем левом углу изображения.
