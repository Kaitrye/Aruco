# Aruco

#### Код:

**Detect_Markers.cpp** - поиск маркеров на изображениях и автоматическое сохранение полученных изображений (с отмеченными маркерами). Рассматривается только 1 словарь (5x5).

**Generate_Markers.cpp** - генерация рандомных ArUco-маркеров.

**Detect_MarkersALL.cpp** - поиск ArUco-маркеров на изображениях в заданной директории среди 4-х словарей (4x4, 5x5, 6x6, 7x7). Сохранение полученных изображений с отмеченными маркерами в заданную директорию и запись результата в выходной файл.

**Calibrate_camera.cpp** - калибровка камеры по заданному каталогу полученных фотографий шахматной доски.

**Find_All.cpp** - нахождение расстояния от камеры до маркера и матрицы трехмерного поворота.
**Probability.cpp, Aruco2.ipynb** - анализ вероятности распознавания маркеров с расстояний от 1 до 20 метров на наборе из 50 маркеров разной размерности (5, 10 и 15 см).
